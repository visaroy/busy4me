# busy4me
busy4me process

busy4 depends on below libraries:

Boost 1.48 or later
And uses below toolkit to build libraries and executalbes:

CMake 3.1.0 or later
First, we make a root directory of the build tree:

``` shell
cd /path/to/mteval
mkdir build
cd build
```

Then we build the tool:

``` shell
cmake ..
make -j <threads>
```  
