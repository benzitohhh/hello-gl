This is the source code for the "hello world" OpenGL application described in
chapter 2 of Joe Groff's OpenGL tutorial: 

http://duriansoftware.com/joe/An-intro-to-modern-OpenGL.-Chapter-2:-Hello-World:-The-Slideshow.html

You will need the GLUT <http://www.opengl.org/resources/libraries/glut/> and
GLEW <http://glew.sourceforge.net/> libraries to compile this program. It also
requires OpenGL 2.0 or later.

Do whatever you like with this source code.


## To install on OSX

1. `brew install glew`

2. `make clean; make; ./hello-gl`

i.e. `Makefile` is a symlink to `Makefile.MacOSX`