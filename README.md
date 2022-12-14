# 3D Graphic Engines
Repo for 3D Graphic Engines

## Tutorial Sources

### javidx9 (Youtube) - OneLoneCoder
* Original Creator: [javidx9](https://www.youtube.com/c/javidx9) 
* Video #1: [Code-It-Yourself! 3D Graphics Engine Part #1 - Triangles & Projection](https://youtu.be/ih20l3pJoeU)

Create projects: Create a **C++ Windows Console Application** on **Visual Studio** (tested on **VS 2022**) 

<p align="center">
  <img src="/images/1.JPG">
</p>

In `Solution Explorer`, right click on `Source Files` -> `Add` -> `New Item` -> Create the header `olcConsoleGameEngine.h` with the same content as `(/javidx9-OneLoneCoder/)olcConsoleGameEngine.h` in this repo. 

<p align="center">
  <img src="/images/4.JPG">
</p>

Next, copy & paste content of `(/javidx9-OneLoneCoder/)OneLoneCoder_olcEngine3D_Part1.cpp` to the *main cpp file* (in `Source Files` also), then *run/start (F5)*. Observer the result.

<p align="center">
  <img src="/images/3.JPG">
</p>

* Video #2: [Code-It-Yourself! 3D Graphics Engine Part#2 - Normals, Culling, Lighting & Object Files](https://youtu.be/XgMWc6LumG4)

Copy & paste content of `(/javidx9-OneLoneCoder/)OneLoneCoder_olcEngine3D_Part2.cpp` to the *main cpp file*. Next, copy & paste `(/javidx9-OneLoneCoder/)VideoShip.obj` (which is a **triangular mesh** created by `Blender`) to same folder also.
 
 <p align="center">
  <img src="/images/5.JPG">
</p>

Then *run/start (F5)*. Observer the result.

 <p align="center">
  <img src="/images/6.JPG">
</p>

* Video #3: [Code-It-Yourself! 3D Graphics Engine Part #3 - Cameras & Clipping](https://youtu.be/HXSuNxpCzdM)
Same as Video #2, copy & paste content of `(/javidx9-OneLoneCoder/)OneLoneCoder_olcEngine3D_Part3.cpp` to the *main cpp file* and `axis.obj`, `mountains.obj`, `teapot.obj`. To change object: `meshCube.LoadFromObjectFile("<name>.obj");` (Line 463). Use *W,S,A,D* and *arrow keys* to move around.

 <p align="center">
  <img src="/images/7.JPG">
</p>

## Others

### Export to Setup.exe File
* [Source #1](https://youtu.be/iFsLvNO4HKY):

`Extensions` -> `Manage Extensions` -> Download `Microsoft Visual Studio Installer Projects` -> Close VS and open again to install

 <p align="center">
  <img src="/images/8.JPG">
</p>

Right click on `Solution` and `Add` -> `New Project` -> `Setup` or `Setup Wizard` 

 <p align="center">
  <img src="/images/9.JPG">
</p>

Check from `10.JPG` to `14.JPG` to create `Primary Output` and add `Shortcut`. (I ticked all the options here so that i can link with `.obj` file)

 <p align="center">
  <img src="/images/17.JPG">
</p>


Also, in `Configuration Manager`, choose `Build`

 <p align="center">
  <img src="/images/14.JPG">
</p>

Then `Build` -> Check the `Release` folder of the `Project` inside `Solution`

 <p align="center">
  <img src="/images/16.JPG">
</p>

The result is in `Installations` folder.
