# OpenGL Pong
![Game window](Sample.png?raw=true)

A reimplemented version of Pong (1972) in freeGLUT. Left paddle is controlled with `W` and `S`, right paddle with `↑` and `↓`.

## Installing OpenGL
Download the content of GLUT32 folder and follow the steps below.

### GLUT.H
Create a folder called GL under the directory below and put GLUT.H inside that folder:

```
C:\Program Files\Microsoft Visual Studio\*1\*2\VC\Tools\MSVC\*3\include
```
*1 Your version of Visual Studio (2017 | 2019 | 2022)

*2 Your edition of Visual Studio (Community | Professional | Enterprise)

*3 Your version of C++ build tools (e.g 14.16.27023)

Example:
```
C:\Program Files\Microsoft Visual Studio\2022\Community\VC\Tools\MSVC\14.32.31326\include\GL\GLUT.H
```

### GLUT32.LIB
Put GLUT32.LIB inside lib folder of your Visual Studio:

```
C:\Program Files\Microsoft Visual Studio\*1\*2\VC\Tools\MSVC\*3\lib\x86
```

Example:
```
C:\Program Files\Microsoft Visual Studio\2022\Community\VC\Tools\MSVC\14.32.31326\lib\x86\GLUT32.LIB
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
