# Stava

Stava is a static program analysis for identifying stack allocable objects of code written in Java. With the results generated, a JVM can be instructed to allocate those objects on the stack instead of the heap. Analysis is performed on java bytecode and Stava will only generate partial results if library code is unavailable. This project is based on the [PYE](https://dl.acm.org/doi/10.1145/3337794) framework.

## Getting Started

### Installation
This project only requires a working installation of Java 8. Clone the repo and you're good to go! Use scripts from the [scripts](https://github.com/42niks/stava/tree/master/scripts) package and set them up according to your installation.

## Analysing Code 
Sample scripts are provided in the [scripts](https://github.com/42niks/stava/tree/master/scripts) directory. There are 2 types of usecases for stava.
* Benchmark Code: This code is expected to be precompiled. These can be benchmarks like DaCapo.
* Application Code: This is code written by user that has to be compiled.
More instructions [here](https://github.com/42niks/stava/blob/master/scripts/README.md).

## Built With
* [Soot](https://github.com/soot-oss/soot)- a Java optimization framework which enables this project to look into class files and much more. 

## Authors
* [*Nikhil T R*](https://github.com/42niks)
* [*Dheeraj Yadav*](https://github.com/dheeraj135)
* [*Manas Thakur*](https://manas.gitlab.io) 
