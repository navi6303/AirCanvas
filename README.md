# AIR CANVAS

Air Canvas helps to draw on a screen just by waiving your finger fitted with a 
colorful point or a simple colored cap using OpenCV. The language used is C++ due 
to its huge optimised libraries and easy to use syntax. 

# INSTALLING OpenCV FOR C++

- Step 1: 
Go to https://github.com/opencv/opencv and download the Lastest Release.
Extract Files to local drive e.g. D:

- Step 2:
Add bin folder to the Environment Variables path
D:opencvbuildx64vc15bin
Restart computer

- Step 3:
Create a New Visual Studio project C++ console.
Set the platform target to x64

- Step 4:
Add Directories by going to Project-Properties-Configuration Properties-

VC++ Directories
    1. Add Build Directories: D:opencvbuildinclude
    2. Add Library Directories: D:opencvbuildx64vc15lib
Linker Input 
    3. Add Linker input: opencv_world454d.lib
       d for debug without d for release 

# HOW TO RUN CODE

To begin, create a new item (Shortcut-ctrl+shift+A) and copy the code from the attached .cpp file named "PROJECT_CODE.cpp"
and then paste it. Make sure that only one main function needs to be present in the project at a time. And to detect
some other color run ColourPicker.cpp file, exclude the previous file or item in the project to run this code.
