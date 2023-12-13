[简体中文](README.md) | English

# **HTEffect Demo**
## **Instruction**
- This article introduces how to quickly get through example projects.



<br/>

### **Android**
#### **1. Download**
Execute the following commands in sequence
- git clone https://gitee.com/htai-open/HTEffect_QiNiu_Live_Android.git
- cd HTEffect_QiNiu_Live_Android
- git submodule init && git submodule update

#### **2. Configuration**
After downloading, open Project **HTEffect_QiNiu_Live_Android**
- Replace **label** in AndroidManifest.xml and **applicationId** in build.gradle with your APP name and package name, respectively
- Replace **"YOUR_APP_ID"** with your AppId in **StreamingApplication.java**
- Replace **assets** in **htui** folder with your assets
- Build, Run, and search **init-status** to see relevant logs