Glorex
===================================================

A light-weight cross-platform 3D framework and oriented tools collection for OpenGL ES 3.0 on mobile.

This repository contains Glorex source and the sample code for 10+ 3D demos using Glorex and native c/c++.

*Currently this project's core code is under active development, not guarantee build successfully on master. But you still can get a previously builded well app from [here](http://www.github.com)*

## Features ##
* Focus on mobile(Android/IOS) OpenGL ES3.0+ only
* Use recommended GLSL for rendering, no more fixed pipeline on OpenGL ES1.0
* Text Rendering support (muti-language using UTF-8) 
* Model import support
* Multi-touch control support
* Physics/ Collision Detection/ Animation /Scene Management (will coming soon)
* Nice framework and examples based on a couple of projects (see below)
* Plenty demos (currently 10+ 3D demos) in a single demo app (see below)
* Use Gradle for Building On Android, easy to build

## Technology Stack ##
* Native C/C++
* Opengl ES 3.0
* [GLM](http://glm.g-truc.net/0.9.6/index.html) for graphic math
* [assimp](https://github.com/assimp/assimp) for asset import
* [stb_image](https://github.com/nothings/stb) for image import
* [freetype](http://www.freetype.org/) for TTF import
* [bullet](https://github.com/bulletphysics/bullet3) 3D Real-Time Multiphysics Library

## Content ##
to be add..

## Sample ##

*below is two running demo from the branch "branch-c", witch is sample of simple vertex shader and basic light modal*

 ![colorcube](https://raw.githubusercontent.com/qige023/OpenGL-ES3-Programming-On-Android/master/docs/colorcube.gif)
 
 ![diffusetorse](https://raw.githubusercontent.com/qige023/OpenGL-ES3-Programming-On-Android/master/docs/diffusetorse.gif)
 
 to be add..

## Support Platforms ##
This project currently target on Android only, IOS support will be in consider later

builds and test on the following platforms:

* Android 4.3+ NDK (C/C++)
* Android 4.3+ SDK (Java)

API Level 18+ on Android 4.3+ (It's the minimal version of Android that support GLES 3.0 :D )

## Builds ##
Need Android sdk & ndk installed

Need Android Studio or Eclipse(with CDT and Gradle plugins) 

libfreetype.a and libassimp.so is needed for build for some demos. Here I provide my own complied version, you can checkout in app/libs folders (tested on Android 4.3). But you can find some useful link and hints about cross-compile skills from docs/reference.md.

Import gradle project, build and enjoy...

to be add..

## Run Demos ##
For Nanosuit Demo, you must place project's sdcard/model folder to your phone's sdcard/Glorex/model .

## Special Thanks ##
*Some parts of framework code inspired by:*

* [OpenGL Shader Language Cookbook](https://github.com/daw42/glslcookbook)
* [Learn Opengl](http://www.learnopengl.com/)

*Some examples and image assets borrow from:*

* [OpenGL ES 3.0 Programming Guide](http://www.opengles-book.com)
* [Nehe OpenGL's Lesson](http://nehe.gamedev.net/)
* [OpenGL Shader Language Cookbook](https://github.com/daw42/glslcookbook)
* [Learn Opengl](http://www.learnopengl.com/)

*Please contact me if some demo assets need more license granted or has free use limitation*

## License ##
The MIT License

## Authors ##
vicky yuqi.fan@foxmail.com

