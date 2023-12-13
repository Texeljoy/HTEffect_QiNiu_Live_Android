简体中文 | [English](README_EN.md)

# **HTEffect Demo**
## **说明**
- 本文介绍如何快速跑通示例工程

<br/>

## **操作步骤**


### **Android**
#### **1. 下载源码**
依次执行以下命令
- git clone https://gitee.com/htai-open/HTEffect_QiNiu_Live_Android.git
- cd HTEffect_QiNiu_Live_Android
- git submodule init && git submodule update

#### **2. 配置工程**
下载完成后，打开HTEffect_QiNiu_Live_Android工程
- 将 AndroidManifest.xml 中的 label 和 build.gradle 中的 applicationId 分别替换为您的应用名和包名
- 将StreamingApplication.java中的 "YOUR_APP_ID" 替换成您的AppId
- 将htui模块中的assets替换为您的assets
- 编译，运行，日志搜索init-status可以查看相关日志
