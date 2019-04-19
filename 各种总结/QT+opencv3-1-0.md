QT+OpenCV3.1.0
=
**亲测有用链接：**
https://blog.csdn.net/chang_shuang/article/details/78239660
----
**基本步骤：**
> 1.安装qt (第三方软件安装在/opt目录下面)
> 2.安装CMake 
> 3.下载opencv-3.1.0和opencv_contrib-3.1.0(已存百度云)
---
**当时用的Cmake指令**
cmake 
-D CMAKE_BUILD_TYPE=Release 
-D CMAKE_INSTALL_PREFIX=/usr/local  
-D OPENCV_EXTRA_MODULES_PATH=/home/din/Software/OpenCV/opencv-3.1.0/opencv_contrib-3.1.0/modules/ ..
-----
**坑1：**刚开始cmake时候用了一上午都有问题，后来重新下载了opencv3.1.0及其contrub，然后就通过了！！！（新下载的source code已经放在百度云里面了～）
**坑2：**
fatal error: stdlib.h: No such file or directory
 #include_next  < stdlib.h >
                          ^
compilation terminated
解决方法：
在编译时候加 -D ENABLE_PRECOMPILED_HEADERS=OFF
---