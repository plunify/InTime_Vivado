![alt text](images/Plunify_Logo_300.png)

# Run InTime in Tcl Mode (Vivado)
This repository contains scripts to run InTime in the Tcl Console or on the command-line. There are 3 ways to run InTime from a Tcl script.
1. From a command line shell
2. Within InTime GUI Tcl Console
3. From the Vivado Tcl Console

## Main Contents
1. [examples](examples/) : Sample designs for the various flows described here.
2. [scripts](scripts/) : Sample scripts to run InTime from each of these clients - command line, InTime GUI or Vivado Tcl console. 
3. [scripts/intime/configuration](scripts/intime/configuration/) : Ways to set up InTime for your FPGA toolchains.

Currently, both project and non-project modes are supported. 
For non-project mode, only a post-synthesis **DCP** file is supported for InTime version 2.6.10 and older. 

To use the InTime GUI, refer to this [video](https://www.youtube.com/watch?v=lQvY_XZ3R7w).
For more information about InTime, go to [here](https://www.plunify.com/en/intime/)

## Requirements
1. Latest version of InTime.
2. Vivado with an appropriate license properly registered in InTime. If you have not done so, please refer to this [page](scripts/intime/configuration)

