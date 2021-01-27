# tolua_runtime_pb
tolua_runtime with lua-protobuf

基于 [tolua](https://github.com/topameng/tolua_runtime) ，替换 protoc-gen-lua 为 lua-protobuf， 并编译各平台的库。

想自己编译可以试一下。不想浪费时间可以直接用Plugins目录里编译好的。或者用编译后且集成好的完整的[tolua_pb](https://github.com/jozhn/tolua_pb)。



## Library

**tolua_runtime 1.0.8.584**

https://github.com/topameng/tolua_runtime

**lua-protobuf 0.3.2**

https://github.com/starwing/lua-protobuf



## Environment

PC: build_win32.sh build_win64.h (mingw + luajit2.0.4)

Android: build_arm.sh build_x86.sh (mingw + luajit2.0.4)

Mac: build_osx.sh (Xcode9.4.1 + luac5.1.5 for luajit can't run on unity5)

iOS: build_ios.sh (Xcode9.4.1 + luajit2.1 beta)

macOS: 10.14.5

Xcode: 9.4.1

NDK: android-ndk-r10e



## Tutorial

tolua编译集成lua-protobuf指南： https://john.js.org/2020/11/02/ToLua-Compile-With-lua-protobuf/
