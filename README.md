# tutorial organization

get all mrpt resources at <http://www.mrpt.org>

***
# quick installation (for windows)

download and install cmake at <https://cmake.org/download/>

download and install wxwidgets at <http://www.wxwidgets.org/downloads/>

open the msvc 64bit command-line prompt (from the start menu -> MSVC -> Visual Studio Tools) 

>$ cd [wxwidgets-dir]/build/msw

>$ nmake -f makefile.vc BUILD=release SHARED=1 RUNTIME_LIBS=dynamic DEBUG_INFO=0 VENDOR=mrpt USE_OPENGL=1 TARGET_CPU=amd64

>$ nmake -f makefile.vc BUILD=debug SHARED=1 RUNTIME_LIBS=dynamic DEBUG_INFO=1 VENDOR=mrpt USE_OPENGL=1 TARGET_CPU=amd64

download and install opencv (2.4.11 strongly recommended) at <http://opencv.org/downloads.html>

use cmake-gui to build mrpt source and generate msvc projects

use visual studio to compile mrpt as normal
