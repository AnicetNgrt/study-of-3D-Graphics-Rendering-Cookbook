### Personal study of "3D Graphics Rendering Cookbook" by Segey Kosarevsky & Viktor Latypov

Bits of code and experiments I made while reading [3D Graphics Rendering Cookbook](https://www.packtpub.com/product/3d-graphics-rendering-cookbook/9781838986193).

Most of the code in this repository is heavily inspired by and/or copied from the book's code samples, which are open-source. Find all the missing bits and pieces in the [official git repository of the book](https://github.com/PacktPublishing/3D-Graphics-Rendering-Cookbook).

### Build on Linux

Add all the assets from the official git repository of the book's `/data/` and `/deps/` directory into this repository's `/data/` and `/deps/` directory.

Make sure you have OpenGL, Vulkan, cmake, make, g++ and Python3

```bash
cd build
cmake .. -G "Unix Makefiles"
make
```

### Run

Go to the root directory of this repository and run binaries located in the `/bin/` directory from there.