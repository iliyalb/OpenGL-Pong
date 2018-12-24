# OpenGL Classic Games
A collection of retro games reimplemented in Open Graphics Library

## Installing OpenGL
Download the content of GLUT32 folder and follow the steps below.

### GLUT.H
Create a folder called GL under the directory below and put GLUT.H inside that folder:

```
C:\Program Files\Microsoft Visual Studio *\VC\include
```

Remember to replace * with corresponding number of your Visual Studio.
If you are using the newer versions of Visual Studio (e.g VS 2017, VS 2019), go to this directory instead:

```
C:\Program Files\Microsoft Visual Studio\*1\*2\VC\Tools\MSVC\*3\include
```
*1 Your version of Visual Studio (2017 | 2019)

*2 Your edition of Visual Studio (Community | Professional | Enterprise)

*3 Your version of C++ build tools (e.g 14.16.27023)

(Mine looks like: C:\Program Files (x86)\Microsoft Visual Studio\2017\Professional\VC\Tools\MSVC\14.16.27023\include\GL\GLUT.H)

### GLUT32.LIB
Put GLUT32.LIB inside lib folder of your Visual Studio:

```
C:\Program Files\Microsoft Visual Studio *\VC\lib
```

Newer versions of Visual Studio:

```
C:\Program Files\Microsoft Visual Studio\*1\*2\VC\Tools\MSVC\*3\lib\x86
```

If you want to deploy x64 applications you may have to look for GLUT64 or just put GLUT32 inside x64 folder.

### GLUT32.DLL
Copy GLUT32.DLL to the following path:

```
C:\Windows\System32
```

If you're using x64 Windows you also have to put this DLL inside:

```
C:\Windows\SysWOW64
```
