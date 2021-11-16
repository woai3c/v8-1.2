## 构建 v8
```
mkdir -p build
(cd build && cmake .. -DBUILD_TESTING=ON) # generate project with tests
cmake --build build                       # add `-j <n>` with cmake >= 3.12
```
