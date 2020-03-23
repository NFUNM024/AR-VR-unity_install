# Unity及安卓开发环境环境安装
### 一、安装Unity3d开发平台
要按顺序依次安装
+ UnitySetup64-5.6.2f1
+ UnityStandardAssetsSetup-5.6.2f1
+ UnitySetup-Android-Support-for-Editor-5.6.2f1.exe

### 二、安装JAVA
### 三、配置JAVA的环境变量
1.右键我的电脑点击属性
2.点击左侧最下面的高级系统设置
![](https://github.com/NFUNM024/tupian/blob/master/2.png "")
3.点击右下角的环境变量
4.新建用户变量 变量名为"JAVA_HOME"，变量值为JAVA的安装路径
5.点击变量名Path，添加变量值%JAVA_HOME%\bin
6.输入Java -version验证安装
### 四、安装安卓开发平台
1.安装sdk开发包——android-sdk_r24.4.1-windows
2.打开SDK Manager.exe，点击install进行更新
### 五、配置Unity环境
1.新建项目进入Unity
2.按顺序打开Edit-->Preferences --> External Tools点击Browse选择JDK和SDK的路径
