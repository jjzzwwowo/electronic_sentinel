# 雷达摄像头·电子哨兵 (Electronic Sentinel)

旨在实现基于 Linux / C++ 的 OpenIPC 摄像头视频流稳定接入与毫米波雷达数据时空对齐融合系统。

## 项目结构
- `include/`: 存放 C++ 头文件
- `src/`: 存放 C++ 源文件
- `CMakeLists.txt`: CMake 编译配置文件

##  编译与运行
```bash
mkdir build && cd build
cmake ..
make
./electronic_sentinel
