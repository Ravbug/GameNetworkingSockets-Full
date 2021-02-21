# GameNetworkingSockets-Full
Self-contained version of Valve's [GameNetworkingSockets](https://github.com/ValveSoftware/GameNetworkingSockets) with all dependencies bundled as source code, 
so you do not need to externally install any dependencies to use it.

## Building
Compiling with CMake is very easy:
1. Clone or download this repository as zip
2. Extract and enter the root directory
3. Execute in terminal: 
```sh
mkdir build && cd build
cmake ..
cmake --build . --config Release --target GameNetworkingSockets_s
```
All dependencies will be compiled from source and linked.

## Known issues
1. Currently only the static version of the library is supported.
