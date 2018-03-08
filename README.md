# Controlling-the-Keyboard-and-Mouse-with-GUI-Automation
Knowing various Python modules for editing spreadsheets, downloading files, and launching programs is useful, but sometimes there just aren’t any modules for the applications you need to work with. The ultimate tools for automating tasks on your computer are programs you write that directly control the keyboard and mouse. These programs can control other applications by sending them virtual keystrokes and mouse clicks, justpython3- as if you were sitting at your computer and interacting with the applications yourself. This technique is known as graphical user interface automation, or GUI automation for short. With GUI automation, your programs can do anything that a human user sitting at the computer can do, except spill coffee on the keyboard.  Think of GUI automation as programming a robotic arm. You can program the robotic arm to type at your keyboard and move your mouse for you. This technique is particularly useful for tasks that involve a lot of mindless clicking or filling out of forms.
On Windows, modules to install.open cmd or powershell pip install pyautogui

On OS X, run sudo pip3 install pyobjc-framework-Quartz, sudo pip3 install pyobjc-core, and then sudo pip3 install pyobjc.

On Linux, run sudo pip3 install python3-xlib, sudo apt-get install scrot, sudo apt-get install python3-tk, and sudo apt-get install python3-dev. (Scrot is a screenshot program that PyAutoGUI uses.)

after running the python program open cmd 
type  import pyautogui
>>> pyautogui.displayMousePosition()
show to moving mouse position and you control it
