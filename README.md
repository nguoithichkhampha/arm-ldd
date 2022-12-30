# arm-ldd
a shell script similar with ldd script to check the dependency of arm library.
This script is based on ldd script from https://github.com/crosstool-ng/crosstool-ng

# how to use

## Copy arm-none-linux-gnueabihf-ldd to bin folder of gcc toolchain
## Run with command 
 `arm-none-linux-gnueabihf-ldd --root=${sysroot} ${path_to_library}` 

![Example result](/true.png "Result") 