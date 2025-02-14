---
title: Demo
permalink: /docs/demo/
---

## Requirements

The following demo steps are intended to work after this setup. 
We arbitrary choose Modelica as a target code example, but you can use any other already available in https://github.com/Funz .

  * install OpenModelica on your platform from [OpenModelica website](https://openmodelica.org), so `omc` command will be recognized in your `PATH`
  * get Funz-Modelica distribution: https://github.com/Funz/plugin-Modelica/releases/... (which also include some basic algorithms like gradient descent optimization and root finding)
  * unzip in current test directory: `unzip Funz-Modelica.zip`
  * move in test directory: `cd Funz-Modelica`
  * wake up the 4 Funz 'daemons' which will provide calculation services: `./FunzDaemon_start.sh 4`

We will then work on the 'NewtonCooling' example, which solves a basic PDE on temperature, provided in the `Funz-Modelica/samples` directory:
```
// @ref http://book.xogeny.com/behavior/equations/physical/
model NewtonCooling "An example of Newton's law of cooling"
  parameter Real T_inf=25 "Ambient temperature";
  parameter Real T0=90 "Initial temperature";
  parameter Real h=0.7 "Convective cooling coefficient";
  parameter Real A=1.0 "Surface area";
  parameter Real m=0.1 "Mass of thermal capacitance";
  parameter Real c_p=1.2 "Specific heat";
  Real T "Temperature";
initial equation
  T = T0 "Specify initial value for T";
equation
  m*c_p*der(T) = h*A*(T_inf-T) "Newton's law of cooling";
end NewtonCooling;
```
Our engineering goal is to adjust cooling convection in order to control the minimum temperature reached.
So, in order to 'Funzify' this model, we will just replace the numerical value of the convection coefficient by a parametrized expression:
<pre class="highlight"><code>// @ref http://book.xogeny.com/behavior/equations/physical/
model NewtonCooling "An example of Newton's law of cooling"
  parameter Real T_inf=25 "Ambient temperature";
  parameter Real T0=90 "Initial temperature";
  parameter Real h=<font style="background-color:rgb(255,200,0)">$convection</font> "Convective cooling coefficient";
  parameter Real A=1.0 "Surface area";
  parameter Real m=0.1 "Mass of thermal capacitance";
  parameter Real c_p=1.2 "Specific heat";
  Real T "Temperature";
initial equation
  T = T0 "Specify initial value for T";
equation
  m*c_p*der(T) = h*A*(T_inf-T) "Newton's law of cooling";
end NewtonCooling;
</code></pre>
... and now play with this 'functional' wraping ...

<hr/>

We use `Funz.sh` (or `Funz.bat`) to launch Funz calculations from command-line `bash` (or `cmd.exe`).
You can also get the same results using R, python or Java scripts, with adapted commands. 


## Basic parametric run

Launching 4 calculations for different `convection` values (0.5, 0.6, 0.7, 0.8) is done as follows:
```bash
./Funz.sh Run -m Modelica -if samples/NewtonCooling.mo.par -iv convection=0.5,0.6,0.7,0.8,0.9,1.0 -oe "min(T)" -v 0 -pf "convection" "min(T)" "info"
```
and returns:
```
| convection | min(T)            | info          |
|------------|-------------------|---------------|
| 0.5        | 25.98653154436357 | Run succeded. |
| 0.6        | 25.43373687652521 | Run succeded. |
| 0.7        | 25.19937564256052 | Run succeded. |
| 0.8        | 25.08828738995784 | Run succeded. |
| 0.9        | 25.04045790290655 | Run succeded. |
| 1.0        | 25.01947293170708 | Run succeded. |
```


## Algorithm-driven root finding

Now we will ask a (quite simple) algorithm to find the `convection` value leading to `min(T) = 0.3` (with relative precision of 0.01 on `convection` value):
```bash
./Funz.sh Run       -m Modelica -if samples/NewtonCooling.mo.par -iv convection=0.5,0.6,0.7,0.8,0.9,1.0 -oe "min(T)" -v 0 -pf "convection" "min(T)" "info"
./Funz.sh RunDesign -m Modelica -if samples/NewtonCooling.mo.par -iv convection=[0.5,1.0] -oe "min(T)" -d Brent -do ytarget=25.2 ytol=0.01 -v 0
```
which returns:
```

```


