# NADIN

This is the repo for UPRM's research project on detecting network attacks, specifically sinkhole and wormhole, on RPL WSN.

## Coding Guidelines

We will be using a styling guide for all of our code. This makes code easier to read and maintain.


## C++ projec structure

```
build/
doc/
libs/
src/
test/
CMakeLiist.txt
```
build - used to build the project. Must be excluded with gitignore.
doc - folder for the documentation of the code.
libs - used to house third party libraries.
src - where our code goes.
test - where test program if they are needed.
CMakeList.txt - file to automate compilation with cmake.


Actual:
### C++ Structure
Using the [C++ structure guide](https://medium.com/heuristics/c-application-development-part-1-project-structure-454b00f9eddc).
Since we won't be making a public API we will not use include directory. The libs may be used, but not for now, this is so that you dynamically use the library for the simulation. The test directory will not be used. The build directory will be created locally and must be added to the .gitignore file.

### Clang
[Initial guide](https://leimao.github.io/blog/Clang-Format-Quick-Tutorial/)
## Contributors

Advisor: Dr. Nayda Santiago
Members:
- James O. Rodriguez Feliciano
- Bryan Parra Irizarry
- Yahir A. Torres Galarza
- Manuel A. Infante Degro
- Fabiola Rozas
