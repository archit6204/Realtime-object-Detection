# Realtime-object-Detection
Deep learning based real time object detection system using Darknet and yolo v3.
Sources: 1: https://pjreddie.com/darknet/
         2: https://github.com/AlexeyAB/darknet



Requirements

Windows or Linux

CMake >= 3.8 for modern CUDA support: https://cmake.org/download/

CUDA 10.0: https://developer.nvidia.com/cuda-toolkit-archive (on Linux do Post-installation Actions)

OpenCV >= 2.4: use your preferred package manager (brew, apt), build from source using vcpkg or download from OpenCV official site (on Windows set system variable OpenCV_DIR = C:\opencv\build - where are the include and x64 folders image)

cuDNN >= 7.0 for CUDA 10.0 https://developer.nvidia.com/rdp/cudnn-archive (on Linux copy cudnn.h,libcudnn.so... as desribed here https://docs.nvidia.com/deeplearning/sdk/cudnn-install/index.html#installlinux-tar , on Windows copy cudnn.h,cudnn64_7.dll, cudnn64_7.lib as desribed here https://docs.nvidia.com/deeplearning/sdk/cudnn-install/index.html#installwindows )

GPU with CC >= 3.0: https://en.wikipedia.org/wiki/CUDA#GPUs_supported

on Linux GCC or Clang, on Windows MSVC 2015/2017/2019 https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community
Compiling on Windows by using Cmake-GUI as on this IMAGE: Configure -> Optional platform for generator (Set: x64) -> Finish -> Generate -> Open Project -> x64 & Release -> Build -> Build solution

Compiling on Linux by using command make (or alternative way by using command: cmake . && make )
