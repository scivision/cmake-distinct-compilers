# cmake-distinct-compilers

CMake project with different compilers for different directories via ExternalProject

```sh
cmake -Bbuild

cmake --build build

cmake --install build
```

results in binary files:

```
build/project/subproject01/libsubproject01.so
              subproject02/libsubproject02.so
```
