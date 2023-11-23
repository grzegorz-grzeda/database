# database

Small and simple file system based database library.

This is a [G2EPM](https://github.com/grzegorz-grzeda/g2epm) library.

## How to compile and link it?

Just include this directory in your CMake project.

Example `CMakeLists.txt` content:
```
...

add_subdirectory(<PATH TO THIS LIBRARY>)
target_link_libraries(${PROJECT_NAME} PRIVATE database)

...
```

# Copyright
This library was written by G2Labs Grzegorz Grzęda, and is distributed under MIT Licence. Check the `LICENSE` file for more details.