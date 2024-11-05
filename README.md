# VSCode_OpenFOAM-debug
This repo contains the Visual Studio Code setup files (.vscode folder) used to compile and debug OpenFOAM code

It is intended as a useful plug-and-play tool for debugging OpenFOAM code using VSCode. 
It works in the presented tutorials using OpenFOAM-12 and OpenFOAM-11, no guarantee is provided that it works 
also on other distributions and cases.


Steps needed to debug OpenFOAM code using VS Code:
- Compile OpenFOAM in debug mode
- Download VSCode application and C++ extensions (C/C++ for Visual Studio Code, C/C++ Extension Pack)
- Download cppdbg debugger
- Download the .vscode folder and place it in the folder containing an OpenFOAM case
- Copy the .C file you want to debug and its dependancies inside the OpenFOAM case folder
- Place the breakpoints and press F5 to start debugging
