﻿# TaoCommon

## 简介

收集一些常用的Qt后端代码，以便以后复用。

必须是经过实际项目验证过的。

## 内容

按文件夹分类

## Logger

  日志模板，来自[TaoLogger项目](https://github.com/jaredtao/taologger)

## Thread

  Qt多线程模板，来自[TaoThread项目](https://github.com/jaredtao/TaoThread)

  包括对Qt的Worker-Controller多线程模型的封装。

## Common

  一些通用的代码段。

  |文件名|功能|
  | ---- | -------------------------------- |
  |FileReadWrite.h|文件读写、Json读写|
  |ObjectMap.h|基础对象存储器;优先级对象存储器|
  |Singleton.hpp|单例模板|
  |Subject.hpp|观察者模板|
  |Common.h|QString 支持std::map; <br/>C++11 的 enum 和 int互转; <br/> 计算md5; <br/> 计算percent字符串;<br/> 简易socket数据封包、拆包|

## 使用方式

### 用法(1) -- 作为Qt模块安装

TaoCommon本身是一个Qt模块，可以通过make install的方式，直接安装进QTDIR，只需要执行以下命令：

```shell
qmake
make
make install
```

也可以通过QtCreator执行安装:

打开TaoCommon项目，在 QtCreator的 "项目->Build 步骤" 中，添加一个 make install步骤进行安装。

![](doc/QtCreaterInstall.png)

### 用法(2) -- 包含源码

直接在你的项目中包含TaoCommon.pri文件，

include(TaoCommon/src/TaoCommon/TaoCommon.pri)

## 联系方式:

***

| 作者 | 涛哥                           |
| ---- | -------------------------------- |
|开发理念 | 传承工匠精神 |
| QQ   | 759378563                  |
| 微信 | xsd2410421                       |
| 邮箱 | jared2020@163.com                |
| blog | https://jaredtao.github.io |

***

QQ(TIM)、微信二维码

<img src="https://gitee.com/jaredtao/jaredtao/raw/master/img/qq_connect.jpg?raw=true" width="30%" height="30%" /><img src="https://gitee.com/jaredtao/jaredtao/raw/master/img/weixin_connect.jpg?raw=true" width="30%" height="30%" />


###### 请放心联系我，乐于提供咨询服务，也可洽谈有偿技术支持相关事宜。

***
#### **打赏**
<img src="https://gitee.com/jaredtao/jaredtao/raw/master/img/weixin.jpg?raw=true" width="30%" height="30%" /><img src="https://gitee.com/jaredtao/jaredtao/raw/master/img/zhifubao.jpg?raw=true" width="30%" height="30%" />

###### 觉得分享的内容还不错, 就请作者喝杯奶茶吧~~
***

