<div align="center">

## Comments \- the Good, the Bad, and the Ugly


</div>

### Description

This article discusses commenting: why we use it, how to do so properly, and how to avoid poor practices and pitfalls.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Peter M\. Dodge](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/peter-m-dodge.md)
**Level**          |Beginner
**User Rating**    |4.4 (31 globes from 7 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0, VB Script, VBA MS Access, VBA MS Excel
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__1-43.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/peter-m-dodge-comments-the-good-the-bad-and-the-ugly__1-40255/archive/master.zip)





### Source Code

<br><br>
<b>Commenting: the Good, the Bad, and the Ugly</b><br>
A guide to proper commenting practices by Peter Dodge<br><br>
<b>What is a comment?</b><br>
A comment in Visual Basic is any statement that starts with either an apostrophe (') or the keyword "REM" (short for remark). Used properly, comments a a powerful tool to clarify your program.<br><br>
<b>Why do we use commenting?</b><br>
Programmers use comments to document their code, to explain why a code is doing certain actions, and to document the uses of various variables.<br><br>
<b>What are good, common commenting practices?</b><br>
There are many good commenting practices in the programming industry. Some of the more common ones are outlined below:<br><br>
<i>Variable Documentation</i><br>
A very frequently encountered use of commenting is to document variables and how they are used.<br>
For example:<br><br>
' The length of the longest side.<br>
Dim a as Integer<br>
' The lengths of the other sides.<br>
Dim b as Integer<br>
Dim c as Integer<br><br>
As some people reading this article have noted, these variable names are not very descriptive. The use of descriptive variable names is beyond the scope of this article.<br><br>
<i>Block Header Comments</i><br>
A good but often overdone commenting process is making headers for you forms and modules, explaining the purpose of the file. Revision history can also be added here.<br><br>
<i>Procedure Header Comments</i><br>
A not so often used but very good commenting practices is to have a large haeder at the beginning of a procedure or function explaining the purpose of the fucntion or sub. Function headers should also include the nature of the data returned.<br><br>
<b>When comments get bad</b><br>
Comments, however can be used in bad ways as well, like many other programming practices.
The main incorrect use of comments is when the comment merely explains what the code does. This is nothing that the programmer looking at the code could not deduce. The proper use of comments is to not only explain what the line(s) of code is doing but <i>why</i> the code is doing this. This makes the line(s) of code in question much easier to understand, and makes the original intention of the code clear.<br><br>
Another point of content with comments is if they are left unmaintained after they are written. When this happens, the comment can be misleading. This can cause serious problems, especially in maintainance programming.<br><br>
<b>Conclusion</b><br>
Comments, like most things, is neither inherently good or bad. It is the way in which they are used which makes them good or bad. This article attempts to show the things to try and the things to avoid.<br><br>
<b>Bibliography</b><br>
<i>Code Complete</i>, Microsoft

