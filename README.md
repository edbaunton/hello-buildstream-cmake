# hello-buildstream-cmake
Simple Hello World C application built with Buildstream over CMake

## How to Build

For the easiest build (from a Macbook here), first you will need to clone or copy `bst-here` from [BuildStream](https://gitlab.com/BuildStream/buildstream/blob/master/contrib/bst-here).

Once you have  `bst-here` which is a script to drop you inside a Docker container, you run the following:

```
$ /path/to/bst-here
# Build the project
$ bst build cmake.bst
# ... let it build ...
# Drop into a shell that contains the build artifacts
bst shell cmake.bst
# Run our binary
$ ./usr/bin/hello
Hello, world
```
