#Description
--------------------------------------------------------------
Compilation of x86 and x64 version for Window 10 of SNAPHU Version 1.4.2, 
Statistical-Cost, Netowrk-Flow Algorithm for Phase Unwrapping
Author: Curtis W. Chen

Reproducible build and binaries for SNAPHU Window 10 Version 
Under binding of Cmake and Visual Studio 16 2019 Licences 


Copyright See LICENCE file



#Credits
-------------------------------------------------------------
SNAPHU
Statistical-Cost, Netowrk-Flow Algorithm for Phase Unwrapping
Author: Curtis W. Chen
Version 1.4.2, January 200

Build for Win:
-------------------------------------------------------------
# 2020.03.18  "Muhire Desire"  Cmake Visual Studio 16 2019


#Task done:
-------------------------------------------------------------
-Compilation of x86 and x64 version for window
Binaries are respectively in bin folder.

-Easy install for x64:

copy snaphu-1.4.2_vc_win to C:\

-Add path by commandline or manualy
set PATH=%PATH%;C:\snaphu-1.4.2_vc_win\bin\x64

#To re-build Visual Studio:
-------------------------------------------------------------

mkdir build
cd build
mkdir build86
mkdir build64
cmake -G "Visual Studio 16 2019" -A Win32 -S "Replace path to /snaphu-1.4.2_vc_win/src" -B "build32"
cmake -G "Visual Studio 16 2019" -A x64 -S "C:/Users/7/Documents/GitHub/snaphu/snaphu-1.4.2_vc_win/src" -B "build64"
cmake --build build32 --config Release
cmake --build build64 --config Release


#Reproducible build and binaries for SNAPHU Window 10 Version : 
--------------------------------------------------------------

Build under License binding of Cmake and Visual Studio 16 2019 Licences 


#Else The MIT License Copyright 2020 "Muhire Desire"  
--------------------------------------------------------------
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.










