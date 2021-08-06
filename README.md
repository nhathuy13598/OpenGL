# OpenGL
Learn how to use OpenGL
<!-- TABLE OF CONTENTS -->
<summary><h2 style="display: inline-block">Table of Contents</h2></summary>
<ol>
	<li>
    	<a href="#about-the-project">About The Project</a>
  	</li>
  	<li>
    	<a href="#getting-started">Getting Started</a>
		<ul>
        	<li><a href="#windows">Windows</a></li>
        	<li><a href="#linux">Linux (Ubuntu)</a></li>
      	</ul>
  	</li>
</ol>

<!-- ABOUT THE PROJECT -->
## About The Project
A small project to learn how to use OpenGL. The tutorials come from series
[OpenGL](https://www.youtube.com/watch?v=W3gAzLwfIP0&list=PLlrATfBNZ98foTJPJ_Ev03o2oq3-GGOS2&ab_channel=TheCherno) 
of [The Cherno Youtube Channel](https://www.youtube.com/user/TheChernoProject)

<!-- GETTING STARTED -->
## Getting Started
This is how to build the project in specific OS

### Windows
* Install MSYS2 according to the [official site](https://www.msys2.org/)
* Install GLFW
```console
pacman -S mingw-w64-x86_64-glfw
```
* Install GLEW
```console
pacman -S mingw-w64-x86_64-glew
```
* Install CMake
```console
pacman -S mingw-w64-x86_64-cmake
```
### Linux
* Install GLFW
```console
sudo apt-get install libglfw3-dev
```
* Install GLEW
```console
sudo apt-get install -y libglew-dev
```
* Install CMake
```console
sudo snap install cmake
```
