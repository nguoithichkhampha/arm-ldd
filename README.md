# arm-ldd
a shell script similar with ldd script to check the dependency of arm library

# how to use

## Copy arm-none-linux-gnueabihf-ldd to bin folder of gcc toolchain
## Run with command 
 `arm-none-linux-gnueabihf-ldd --root=${sysroot} ${path_to_library}` 

![Example result](/true.png "Result") 