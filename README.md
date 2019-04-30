
This is a clone of the (silly) [PadLeft](https://github.com/CPPLondonUni/padleft)
library -- but the CMakeLists.txt file seems to be empty!

Your task is to re-write CMakeLists.txt for this project.

Your CMake project definition should consist of two targets:

 1. A *library target* named `padleft` with the source file `src/padleft.cpp`.
    The public headers for this library live in the `include/` directory
    
 2. An *executable target* named `test_padleft`, using the source files
    `test/test_padleft.cpp` and `test/catch_main.cpp`. This target should link
    with the `padleft` target
    
Your project definition should also require a minimum CMake version of 3.1,
and that it uses the C++ language (only).
    
Have fun!