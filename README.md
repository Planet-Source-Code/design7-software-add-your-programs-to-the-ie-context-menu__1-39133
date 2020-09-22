<div align="center">

## Add your programs to the IE context menu\!\!\!


</div>

### Description

Have you ever seen that menu items that appear in the IE context menu, that menu that appears when you right click?

Well, this tutorial will teach you how to add you programs to that menu so when you click on that menu item a program or internet URL will open
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Design7 Software](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/design7-software.md)
**Level**          |Intermediate
**User Rating**    |3.0 (18 globes from 6 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0, VB Script, ASP \(Active Server Pages\) , VBA MS Access, VBA MS Excel
**Category**       |[Internet/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-html__1-34.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/design7-software-add-your-programs-to-the-ie-context-menu__1-39133/archive/master.zip)





### Source Code

<p><font face="Arial" color="#000080" size="6">How to add your programs to the
Internet Explorer context menu</font></p>
<p><font face="Arial" size="4">Have you ever seen that menu items that appear in
the IE context menu, that menu that appears when you right click?<br>
Well, this tutorial will teach you how to add you programs to that menu so when
you click on that menu item a program or internet URL will open</font></p>
<p><font face="Arial" size="4"><b>To run a program from the context menu:</b></font></p>
<p><font face="Arial" size="4">To add a menu item to the IE context menu first
run regedit.exe, located in the Windows folder, then create a registry group in
the group "HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\MenuExt",
then name that new group with the text that you want to appear in the menu item,
now you have the menu item.<br>
The next step is to giving the menu item a file to open or run, to do this open
the group you have created and double click in the key that is named
"(Default)" and change it's value to the program you want to run</font></p>
<p><font face="Arial" size="4"><b>To open a URL from the context menu</b></font></p>
<p><font face="Arial" size="4">Do the same steps, only replace the program path
with the path of an HTML file, to do this create an HTML file, and put the
following code on it, remeber that the context menu cannot point directly into a
URL, that is that you can't put the URL directly into the registry value.</font></p>
<p><font face="Arial" size="4" color="#800080">&lt;script
language=&quot;JavaScript&quot;&gt;<br>
&lt;!--<br>
window.location=&quot;http://www.planetsourcecode.com&quot;;<br>
//--&gt;<br>
&lt;/script&gt;</font></p>
<p><font face="Arial" size="4">and put the URL you wan open.</font></p>
<p><font face="Arial" size="4">And that's all, now to view your new menu open
Internet Explorer and then right click inside the document opened, and now look
for your menu, it will be there, now click it and the file or URL that you
specified will be opened.</font></p>
<p><font face="Arial" size="4">Here ends this tutorial, if you liked this
tutorial please vote for it and post your comments.</font></p>

