# freecad-pluginloader


#
#
# version for local install 
#

Install
-------


create the directory UserAppData/Mod/plugins

download the zipfile  of the complete project to your computer.

unzip it  - you will get a directotry freecad-pluginloader-master

move the content of this directory  into  UserAppData/Mod/plugins

you can modify this file if you want: pluginloaderconfig.yaml



You can also use this script, it makes the same:

https://raw.githubusercontent.com/microelly2/freecad-pluginloader/master/installer.py

Copy and paste into the FreeCAD python comsole window

It works on Linux. 

Use
---

start FreeCAD

A dockwindow will arise may be hidden, you can open it Menu View -> Views -> Pluginmanager

The bottom item starts the installer dialog
 
Select the plugins you want to install

Click Button install/update

Configure
---------

The configruation file is .FreeCAD/Mod/plugins/pluginloaderconfig.yaml

Section plugins

For each plugin create a subsection with its name.

required attributes:

  source

  sourcedir

  destdir






