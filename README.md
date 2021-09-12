# JDKReadNote
JDK读书笔记

## 目录
- [JDKReadNote](#jdkreadnote)
  - [目录](#目录)
  - [背景](#背景)
  - [读代码入手切入点](#读代码入手切入点)
  - [读取代码的开发工具](#读取代码的开发工具)

## 背景

该笔记用且仅用于[OpenJDK](https://github.com/BarryLoo/jdk)的tag版本 _jdk8-b120_ 

该笔记暂时不考虑JDK编译。如果想了解编译细节，按照[README-builds.html](http://hg.openjdk.java.net/jdk8/jdk8/raw-file/tip/README-builds.html)该文档操作。如果有问题，请通过[OpenJDK官方联系方式](https://mail.openjdk.java.net/mailman/listinfo)咨询问题


## 读代码入手切入点

* 根目录的[ReadMe](https://github.com/BarryLoo/jdk/blob/jdk8-b120/README)
* [README-builds.html](http://hg.openjdk.java.net/jdk8/jdk8/raw-file/tip/README-builds.html)

根据以上两本文将可将JDK主要分为

|内容|描述|
|:-|:-|
|hotspot|搭建JDK热启动虚拟机|
|langtools|jdk的javac入口和java语言工具|
|jdk|jdk的编译文件用于构建OpenJDK运行库以及misc文件|
|jaxp|jdk的JAXP（XML）方法实现|
|jaxws|jdk的JAX-WS方法实现|
|corba|jdk的Corba方法实现|
|nashorn|jdk的JavaScript的语言实现|

## 读取代码的开发工具

由于需要看代码实现以及调用过程。读取代码的开发工具需要支持C/CPP、Java和Git。以及对C/CPP的编译支持能力。

* Visual Studio Code（配合C/C++ Extension、Java Extension、Git Extension）
* 系统安装[CygWin](https://www.cygwin.com/)（全包安装）、[Msys](https://www.msys2.org/)（需要安装）、[mingw-w64](http://mingw-w64.org/doku.php/start)

