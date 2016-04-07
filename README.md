# tutorial organization

get all mrpt resources at <http://www.mrpt.org>

get precompiled installation at <http://www.mrpt.org/download-mrpt/>

***
# quick installation (for windows)

download and install cmake at <https://cmake.org/download/>

download and install wxwidgets at <http://www.wxwidgets.org/downloads/>

open the msvc 64bit command-line prompt (from the start menu -> MSVC -> Visual Studio Tools) 

>$ cd [wxwidgets_dir]/build/msw

>$ nmake -f makefile.vc BUILD=release SHARED=1 RUNTIME_LIBS=dynamic DEBUG_INFO=0 VENDOR=mrpt USE_OPENGL=1 TARGET_CPU=amd64

>$ nmake -f makefile.vc BUILD=debug SHARED=1 RUNTIME_LIBS=dynamic DEBUG_INFO=1 VENDOR=mrpt USE_OPENGL=1 TARGET_CPU=amd64

download and install opencv (2.4.11 strongly recommended) at <http://opencv.org/downloads.html>

download mrpt source code at <http://www.mrpt.org/download-mrpt/>
[zip](https://raw.githubusercontent.com/hitrobotgroup/mrpt_org/master/src/mrpt-1.3.1.zip)

use cmake-gui to build mrpt source and generate msvc projects

use visual studio to compile mrpt as normal

# optional resources

get source zips as follow
* [ffmpeg](https://raw.githubusercontent.com/hitrobotgroup/mrpt_org/master/src/ffmpeg-r16537-gpl-lshared-win32.tar.bz2)
* [flexiport](https://raw.githubusercontent.com/hitrobotgroup/mrpt_org/master/src/flexiport-master.zip)
* [ippicv](https://raw.githubusercontent.com/hitrobotgroup/mrpt_org/master/src/ippicv-windows-20141027.zip)
* [opencv_contrib](https://raw.githubusercontent.com/hitrobotgroup/mrpt_org/master/src/opencv_contrib-master.zip)
* [hokuyoaist](https://raw.githubusercontent.com/hitrobotgroup/mrpt_org/master/src/hokuyoaist-master.zip)

get manuals as follow
* [mrpt_book](https://raw.githubusercontent.com/hitrobotgroup/mrpt_org/master/man/mrpt_book.pdf)
* [mrpt_book-chs](https://raw.githubusercontent.com/hitrobotgroup/mrpt_org/master/man/mrpt_book-chs.pdf)
* [mrpt_tool-chs](https://raw.githubusercontent.com/hitrobotgroup/mrpt_org/master/man/mrpt_tool-chs.pdf)
* [slam_for_dummies](https://raw.githubusercontent.com/hitrobotgroup/mrpt_org/master/man/slam_for_dummies.pdf)
* [slam_thesis_mead](https://raw.githubusercontent.com/hitrobotgroup/mrpt_org/master/man/slam_thesis_mead.pdf)
