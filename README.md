# Premake Practice Project OpenGL Triangle
This is a practice project for learning how to use Premake 5, in the context of building a project with OpenGL.

## Building
### Linux
1. Install a C++ compiler. Your package manager should have one. I use [GCC](https://gcc.gnu.org/), but you can also use [Clang](https://clang.llvm.org/)
2. Install [Premake](https://premake.github.io/download). Your package manager will probably have this, too
3. Run `premake5 gmake2` in the root directory of this project, to generate a makefile
4. Run `make` in the root directory of this project, to build the project

### Windows
1. Install [Visual Studio](https://visualstudio.microsoft.com/downloads/)
2. Download [Premake](https://premake.github.io/download) and put it on your path
3. Run `premake5 vs2022` in the root directory of this project
4. Open the generated solution file in Visual Studio
