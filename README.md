# VEX.CDT
Vexanium Contract Development Toolkit

## Version : 1.6.1
To make your life easier we provide you a debian installer in this version.  
Yep, you don't need to compile and build, just install it.  
> Requirements: Ubuntu 18 64 bit with recommended 8 GB RAM  

Download here:  
```wget https://vexanium.s3-ap-southeast-1.amazonaws.com/dl/vex.cdt.amd64.deb```  
Then install it:  
```sudo apt install ./vex.cdt.amd64.deb```   
The installation process of vex.cdt.amd64.deb [Version: 1.6.1] only tooks approximately 2 minutes, much much faster than manually building the vex.cdt repository [version 1.5.0] even with 8 GB RAM that tooks about 3 hours.

## Version : 1.5.0
Below are guides for compiling this repository's source codes

### Guided Installation (Building from Scratch)
Follow commands below step by step
```sh
$ git clone --recursive https://github.com/vexanium/vex.cdt
$ cd vex.cdt
$ ./build.sh
$ sudo ./install.sh
```
> 4 GB RAM tooks approximately 9 hours  
> 8 GB RAM tooks approximately 3 hours  
> 16 GB RAM tooks approximately 2 hours  

### Installed Tools
---
* eosio-cpp
* eosio-cc
* eosio-ld
* eosio-init
* eosio-abigen
* eosio-abidiff
* eosio-pp (post processing pass for WASM, automatically runs with eosio-cpp and eosio-ld)
* eosio-wasm2wast
* eosio-wast2wasm
* eosio-ranlib
* eosio-ar
* eosio-objdump
* eosio-readelf
