Competitive setup for QtCreator
==============================

Description:
------------
This wizard made for QtCreator to easy setup for competitive tasks.
Removed unnesesary wizard pages. Only one build system left (but you can change it, see below)
Also prepared \*.cpp template for competitive programming (typedefs, defines, int main(){} ).

Installation:
-------------
1. Create a new folder "competitive" in the: 
```QtCreator_install_folder/share/qtcreator/templates/wizards/projects```
2. Copy files from this repo into the new folder.

After that in QtCreator create a new project and select "Competitive".
Then select folder and Kit. Thats all.


Customization:
--------------
You can easily customise template and build system.
To change Build System change the value for key "BuildSystem" in options list in wizard.json:
"cmake" - for CMake build system
"qmake" - for qmake
"qbs" - for Qbs

To customize the cpp file just modify main.cpp as you need.
