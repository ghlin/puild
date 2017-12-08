# puild
simple Makefile generator

# usage

``` bash
# in your project dir.
mkdir build
cd build

# assuming ../src contains your source code.
puild ../src ---p c++1z debug ---o fancy-app ---c -DFANCY_MACRO=1 > Makefile

make

./fancy-app
```
