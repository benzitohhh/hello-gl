This is the source code for the "hello world" OpenGL application described in
chapter 2 of Joe Groff's OpenGL tutorial: 

http://duriansoftware.com/joe/An-intro-to-modern-OpenGL.-Chapter-2:-Hello-World:-The-Slideshow.html

This is also helpful:

https://en.wikibooks.org/wiki/OpenGL_Programming


## To install on OSX


### GLUT

On OSX, `GLUT` framework is already available,
located at `/System/Library/Frameworks/GLUT.framework`.

Note that many of the functions are now deprecated by Apple,
and these functions can cause compile warnings, and also
not show up in TAGS file.

Still, `man` pages are available for most of the functions
(i.e. `man glutInit`)

### GLEW

`GLEW` needs to be installed. So do `brew install glew`.
This installs the header files in `/usr/local/include/GL/`

To add a TAGS file for it:
```
cd /System/Library/Frameworks/GLUT.framework;
sudo ctags -e -R
```


### Building

```
make clean; make; ./hello-gl
```

i.e. `Makefile` is a symlink to `Makefile.MacOSX`

