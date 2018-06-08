1. ​					LLVM，Clang 在windows下编译
2. 下载llvm，clang的source文件，解压
3. 把clang的文件放到llvm的tools中
4. 在跟llvm同级的目录下mkdir build文件夹
5. cd build    输入命令  cmake -G "Visual Studio 15" -Thost=x64  ..\llvm   （也可以用Cmake _gui创建*.sln)
6. with Visual studio2017打开*.sln                     all_build    ->compiler
7. in debug/release 文件夹中





参考：1.https://stackoverflow.com/questions/46553436/building-with-cmake-ninja-and-clang-on-windows

​	2.https://metricpanda.com/rival-fortress-update-27-compiling-with-clang-on-windows