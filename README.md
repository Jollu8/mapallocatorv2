# mapallocator
---

command for running

```
mkdir build
cd build
cmake .. -DPATCH_VERSION=1
cmake --build .
cmake --build . --target test
cmake --build . --target package
./src/mapallocatorv2
```