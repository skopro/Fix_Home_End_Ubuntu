# Fix_Home_End_Ubuntu  
Remap PGUP to HOME and PGDN to END  

  

For find PGUP and PGDN code do :  
**1- Run "xev" command in terminal.  
2- Press PGUP or PGDN.**  
**3- Find the code.** example : state 0x10, keycode 112 (keysym 0xff55, Prior), same_screen YES  ==> code is 112  
  
------------------------------------------------------------------------------

Command for making executable file :   
  **chmod a+x fixHomeEnd.sh**  
  
------------------------------------------------------------------------------

Command for double clicking execution :  
  **gsettings set org.gnome.nautilus.preferences executable-text-activation ask**  

