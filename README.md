# lispbox-updated
The official support of lispbox have stopped. Based on the last version of lispbox v0.7, the next component is updated to its newest version.
Updated Time：2019/01/27
<br />emacs: v26.1   http://www.gnu.org/software/emacs/download.html
<br />Clozure CL: V1.11.5  https://ccl.clozure.com/download.html
<br />Slime: V2.23  https://common-lisp.net/project/slime/#downloading


How to setup the environment:
1. unzip all the files to C:/lispbox
2. set system path.  
   PATH += C:\lispbox\ccl;C:\lispbox\emacs\bin;
3. replace the ecmas init file  ".emacs"
   replace the content  C:/Users/{username}/AppData/Roaming/.emacs  with  C:/lispbox/How-to-setup/configured.emacs
   <br />if the .emacs file doesn't exist, run the lispbox.bat, change some items below menu "Options", and "Save Options", then the .emacs will be created.
