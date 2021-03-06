# Waves Simulator
Improvement on [_**Dynamic Vertex Buffers: Waves Demo**_](http://richardssoftware.net/Home/Post/9) by http://richardssoftware.net/. 

YouTube Preview: http://www.youtube.com/watch?v=Py5x-sKptkA
[![alt tag](https://raw.github.com/CordPRO/WavesSimulator/master/Screenshot2.png)](http://img.youtube.com/vi/Py5x-sKptkA/0.jpg)

Ripples/Waves Simulation using Microsoft Direct Compute
--------------------------------------------------------
Vertex Calculation code is modified to utilize **Microsoft Direct Compute** resulting significant improvements in Performance. 

Reflective and Refractive Water Shader
----------------------------------------
Shaders involving **Reflection** and **Refraction** are also introduced to Water Surface with **Depth Based Blending.**

![alt tag](https://raw.github.com/CordPRO/WavesSimulator/master/Screenshot.png)

SharpDX API
----------------------------------------
This code is based on **SharpDX (Version 3.0)**, which is a .Net based wrapper on **Microsoft Direct X 11** API.
The original code by *richardssoftware.net* utilizes **SlimDX** Wrapper. But I have used **SharpDX** instead of **SlimDX** since **SlimDX** has not received any updates recently. 

Special Thanks
--------------
http://richardssoftware.net and **Eric Richards** for the wonderful SlimDX Direct 3D 11 Tutorial presented in the website.
http://www.rastertek.com/tutdx11.html - **Classic Direct 3D 11 Tutorial** by **Rastertek**
