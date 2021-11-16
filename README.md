## 构建 v8
```
mkdir -p build
cd build
cmake .. -DCMAKE_BUILD_TYPE=debug -DUSE_SNAPSHOT=1
make
```
