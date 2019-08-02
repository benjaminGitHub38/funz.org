---
title: I/O Parser API
permalink: /docs/io_parser/
---



<HTML>
<!-- ========== METHOD SUMMARY =========== -->

<A NAME="method_summary"><!-- --></A>
<TABLE BORDER="1" WIDTH="100%" CELLPADDING="3" CELLSPACING="0" SUMMARY="">
<TR BGCOLOR="#CCCCFF" CLASS="TableHeadingColor">
<TH ALIGN="left" COLSPAN="2"><FONT SIZE="+2">
<B>Method Summary</B></FONT></TH>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#after(java.util.LinkedList, java.lang.String)">after</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines,
      java.lang.String&nbsp;beginstr)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get following part of several Strings</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.lang.String</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#after(java.lang.String, java.lang.String)">after</A></B>(java.lang.String&nbsp;line,
      java.lang.String&nbsp;beginstr)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get the part following of a String</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;double</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#asNumeric(java.lang.String)">asNumeric</A></B>(java.lang.String&nbsp;line)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;wrapp String in float</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;double[]</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#asNumeric1DArray(java.util.LinkedList)">asNumeric1DArray</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;double[]</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#asNumeric1DArray(java.lang.String)">asNumeric1DArray</A></B>(java.lang.String&nbsp;line)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;double[]</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#asNumeric1DArray(java.lang.String, java.lang.String)">asNumeric1DArray</A></B>(java.lang.String&nbsp;line,
                 java.lang.String&nbsp;delim)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;wrapp String in float array</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;double[][]</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#asNumeric2DArray(java.util.LinkedList)">asNumeric2DArray</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;double[][]</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#asNumeric2DArray(java.util.LinkedList, java.lang.String)">asNumeric2DArray</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines,
                 java.lang.String&nbsp;coldelim)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;double[][]</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#asNumeric2DArray(java.lang.String)">asNumeric2DArray</A></B>(java.lang.String&nbsp;line)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;double[][]</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#asNumeric2DArray(java.lang.String, java.lang.String, java.lang.String)">asNumeric2DArray</A></B>(java.lang.String&nbsp;line,
                 java.lang.String&nbsp;coldelim,
                 java.lang.String&nbsp;rowdelim)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;wrapp String in 2D float array</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#before(java.util.LinkedList, java.lang.String)">before</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines,
       java.lang.String&nbsp;beginstr)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get part before of several Strings</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.lang.String</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#before(java.lang.String, java.lang.String)">before</A></B>(java.lang.String&nbsp;line,
       java.lang.String&nbsp;endstr)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get the part before of a String</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#between(java.util.LinkedList, java.lang.String, java.lang.String)">between</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines,
        java.lang.String&nbsp;beginstr,
        java.lang.String&nbsp;endstr)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get the part between delimiters of several Strings</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.lang.String</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#between(java.lang.String, java.lang.String, java.lang.String)">between</A></B>(java.lang.String&nbsp;line,
        java.lang.String&nbsp;beginstr,
        java.lang.String&nbsp;endstr)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get the part between delimiters of a String</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.lang.Boolean</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#contains(java.io.BufferedReader, java.lang.String)">contains</A></B>(java.io.BufferedReader&nbsp;inn,
         java.lang.String&nbsp;keyfilter)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;test if String is in buffer</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.lang.Boolean</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#contains(java.io.File, java.lang.String)">contains</A></B>(java.io.File&nbsp;file,
         java.lang.String&nbsp;keyfilter)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;test if String is in ASCII file</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>&nbsp;java.lang.Boolean</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#contains(java.lang.String)">contains</A></B>(java.lang.String&nbsp;keyfilter)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;test if String is in any file</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>&nbsp;java.lang.Boolean</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#contains(java.lang.String, java.lang.String)">contains</A></B>(java.lang.String&nbsp;filefilter,
         java.lang.String&nbsp;keyfilter)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;test if String is in any file</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#cut(java.util.LinkedList, java.lang.String, int)">cut</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines,
    java.lang.String&nbsp;separator,
    int&nbsp;index)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;split several lines in several parts and keep one of them</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.lang.String</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#cut(java.lang.String, java.lang.String, int)">cut</A></B>(java.lang.String&nbsp;line,
    java.lang.String&nbsp;separator,
    int&nbsp;index)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;split a line in several parts and keep one of them</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>&nbsp;java.lang.String</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#filecat()">filecat</A></B>()</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;concatenante content of files</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.lang.String</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#filecat(java.io.File)">filecat</A></B>(java.io.File&nbsp;f)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;read ASCII content of a file</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>&nbsp;java.lang.String</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#filecat(java.lang.String)">filecat</A></B>(java.lang.String&nbsp;filefilter)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;find matching files and concatenante content</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#filter(java.util.LinkedList, java.lang.String)">filter</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines,
       java.lang.String&nbsp;regexp)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get lines matching given content regexp</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;int[]</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#filterIndexes(java.util.LinkedList, java.lang.String)">filterIndexes</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines,
              java.lang.String&nbsp;regexp)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get lines matching given content regexp</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>&nbsp;java.util.LinkedList&lt;java.io.File&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#find(java.lang.String)">find</A></B>(java.lang.String&nbsp;filefilter)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;find matching filename regexp files</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#get(java.util.LinkedList, int...)">get</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines,
    int...&nbsp;numbers)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.lang.String</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#get(java.util.LinkedList, int)">get</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines,
    int&nbsp;i)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get element of a list of Strings</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#getAfter(java.util.LinkedList, int, int...)">getAfter</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines,
         int&nbsp;after,
         int...&nbsp;numbers)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#getAll(java.util.LinkedList, int)">getAll</A></B>(java.util.LinkedList&lt;java.util.LinkedList&lt;java.lang.String&gt;&gt;&nbsp;lines,
       int&nbsp;i)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get element of a list of String lists</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#getBefore(java.util.LinkedList, int, int...)">getBefore</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines,
          int&nbsp;before,
          int...&nbsp;numbers)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#getBy(java.util.LinkedList, int, int)">getBy</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines,
      int&nbsp;start,
      int&nbsp;step)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get element of a list of Strings</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#getBy(java.util.LinkedList, int, int, int)">getBy</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines,
      int&nbsp;start,
      int&nbsp;step,
      int&nbsp;end)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get element of a list of Strings</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#grep_basic(java.io.BufferedReader, java.lang.String)">grep_basic</A></B>(java.io.BufferedReader&nbsp;inn,
           java.lang.String&nbsp;keyfilter)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;find String in buffer</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#grep(java.io.BufferedReader, java.lang.String)">grep</A></B>(java.io.BufferedReader&nbsp;inn,
     java.lang.String&nbsp;keyfilter)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;find String in buffer</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#grep(java.io.File, java.lang.String)">grep</A></B>(java.io.File&nbsp;file,
     java.lang.String&nbsp;keyfilter)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;find String in ASCII file</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#grep(java.lang.String)">grep</A></B>(java.lang.String&nbsp;keyfilter)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;find String in ASCII files</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#grep(java.lang.String, java.lang.String)">grep</A></B>(java.lang.String&nbsp;filefilter,
     java.lang.String&nbsp;keyfilter)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;find String in ASCII files matching given file name regexp</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#grepIn(java.lang.String, java.lang.String)">grepIn</A></B>(java.lang.String&nbsp;input,
       java.lang.String&nbsp;keyfilter)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;find String in ASCII file</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#lines()">lines</A></B>()</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get lines in ASCII files</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#lines(int...)">lines</A></B>(int...&nbsp;numbers)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get lines in ASCII files</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#lines(java.lang.String)">lines</A></B>(java.lang.String&nbsp;filefilter)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get lines in ASCII files matching given file name regexp</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#lines(java.lang.String, int...)">lines</A></B>(java.lang.String&nbsp;filefilter,
      int...&nbsp;numbers)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get lines in ASCII files matching given file name regexp</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>&nbsp;java.lang.String</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#ls()">ls</A></B>()</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;list files</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>&nbsp;java.lang.String</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#ls(java.lang.String)">ls</A></B>(java.lang.String&nbsp;filefilter)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;list files with matching name given in regexp</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.lang.String</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#property(java.io.File, java.lang.String)">property</A></B>(java.io.File&nbsp;f,
         java.lang.String&nbsp;key)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;reads a property in a properties file</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#property(java.lang.String)">property</A></B>(java.lang.String&nbsp;key)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;reads a property in properties files</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#property(java.lang.String, java.lang.String)">property</A></B>(java.lang.String&nbsp;filefilter,
         java.lang.String&nbsp;key)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;reads a property in properties files matching given file name regexp</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>&nbsp;void</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#removeFilenameFilter()">removeFilenameFilter</A></B>()</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#replace(java.util.LinkedList, java.lang.String, java.lang.String)">replace</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines,
        java.lang.String&nbsp;toreplace,
        java.lang.String&nbsp;replacer)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;replace parts of a String</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.lang.String</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#replace(java.lang.String, java.lang.String, java.lang.String)">replace</A></B>(java.lang.String&nbsp;line,
        java.lang.String&nbsp;toreplace,
        java.lang.String&nbsp;replacer)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;replace parts of a String</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>&nbsp;void</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#setFilenameFilter(java.lang.String)">setFilenameFilter</A></B>(java.lang.String&nbsp;regexp)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#split(java.lang.String, java.lang.String)">split</A></B>(java.lang.String&nbsp;line,
      java.lang.String&nbsp;separator)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;split a line in several parts</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.lang.String</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#strcat(java.lang.String...)">strcat</A></B>(java.lang.String...&nbsp;lines)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;concatenante many strings as lines</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#substring(java.util.LinkedList, int)">substring</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines,
          int&nbsp;begin)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get part of a many String</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#substring(java.util.LinkedList, int, int)">substring</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines,
          int&nbsp;begin,
          int&nbsp;end)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get part of a many String</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#substring(java.util.LinkedList, java.lang.String)">substring</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines,
          java.lang.String&nbsp;beginstr)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get part of a several Strings</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#substring(java.util.LinkedList, java.lang.String, java.lang.String)">substring</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines,
          java.lang.String&nbsp;beginstr,
          java.lang.String&nbsp;endstr)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get part of a several Strings</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.lang.String</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#substring(java.lang.String, int)">substring</A></B>(java.lang.String&nbsp;line,
          int&nbsp;begin)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get part of a String</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.lang.String</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#substring(java.lang.String, int, int)">substring</A></B>(java.lang.String&nbsp;line,
          int&nbsp;begin,
          int&nbsp;end)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get part of a String</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.lang.String</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#substring(java.lang.String, java.lang.String)">substring</A></B>(java.lang.String&nbsp;line,
          java.lang.String&nbsp;beginstr)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get part of a String</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.lang.String</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#substring(java.lang.String, java.lang.String, java.lang.String)">substring</A></B>(java.lang.String&nbsp;line,
          java.lang.String&nbsp;beginstr,
          java.lang.String&nbsp;endstr)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;get part of a String</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.util.LinkedList&lt;java.lang.String&gt;</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#trim(java.util.LinkedList)">trim</A></B>(java.util.LinkedList&lt;java.lang.String&gt;&nbsp;lines)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;remove whitespaces, ...</TD>
</TR>
<TR BGCOLOR="white" CLASS="TableRowColor">
<TD ALIGN="right" VALIGN="top" WIDTH="1%"><FONT SIZE="-1">
<CODE>static&nbsp;java.lang.String</CODE></FONT></TD>
<TD><CODE><B><A HREF="../../../org/promethee/util/ASCII.Parser.html#trim(java.lang.String)">trim</A></B>(java.lang.String&nbsp;line)</CODE>

<BR>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;remove whitespaces, ...</TD>
</TR>
</TABLE>

</HTML>

