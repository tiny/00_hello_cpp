# 00.  hello_cpp
c++ version of basic hello world w/ cmake 

This project will exercise the core tools used for c++ development.
tools include:
- g++
- visual code
- cmake
- github

the program itself will demonstrate:
- what is a comment
- include files
- the main program definition
- calling a function 
- printing to the screen

you should familiarize yourself with the cmake file (CMakeLists.txt)

When creating a repo, always include the README.md file offer by github.  this acts as a coversheet for your project.  The README.md file uses markdown syntax which will be useful to utilize.


First, you must clone this repo.  To clone the repo, first make
a work folder to store your projects. somthing like ~/work will do.
then make that folder the active folder (ie: cd ~/work)

check out the project
```
git clone https://github.com/tiny/00_hello_cpp
```

then change into the newly created folder

``` 
cd 00_hello_cpp
```

make a build area
```
mkdir build
```

change into the build area
```
cd build
```

then build the make file and make the project
```
cmake ..
make
```

now run it
```
./hello
```

