# Unity及安卓开发环境环境安装
### 一、安装Unity3d开发平台
要按顺序依次安装
+ UnitySetup64-5.6.2f1
+ UnityStandardAssetsSetup-5.6.2f1
+ UnitySetup-Android-Support-for-Editor-5.6.2f1.exe

### 二、安装JAVA
![](https://github.com/NFUNM024/tupian/blob/master/12.png "")
+ 最好使用默认路径 更改路径需要记得方便后面安装
### 三、配置JAVA的环境变量
1.右键我的电脑点击属性

2.点击左侧最下面的高级系统设置
![](https://github.com/NFUNM024/tupian/blob/master/2.png "")

3.点击右下角的环境变量

![](https://github.com/NFUNM024/tupian/blob/master/3.png "")

4.新建用户变量 变量名为"JAVA_HOME"，变量值为JAVA的安装路径

![](https://github.com/NFUNM024/tupian/blob/master/4.png "")

5.点击变量名Path，添加变量值%JAVA_HOME%\bin

![](https://github.com/NFUNM024/tupian/blob/master/5.png "")

6.输入Java -version验证安装
### 四、安装安卓开发平台
1.安装sdk开发包——android-sdk_r24.4.1-windows

2.打开SDK Manager.exe，点击install进行更新
![](https://github.com/NFUNM024/tupian/blob/master/7.png "")
### 五、配置Unity环境
1.新建项目进入Unity

2.按顺序打开Edit-->Preferences --> External Tools点击Browse选择JDK和SDK的路径

![](https://github.com/NFUNM024/tupian/blob/master/8.png "")

3.配置好后点击File-->build setting-->add open scenes(选择场景)-->Platfrom选择andorid

![](https://github.com/NFUNM024/tupian/blob/master/9.png "")

4.点击player sitting将package name和company name更改为com.humei.sj

![](https://github.com/NFUNM024/tupian/blob/master/10.png "")

5.点击build创建APK文件

![](https://github.com/NFUNM024/tupian/blob/master/11.png "")

### 六、成品使用录屏
[APK使用录屏](https://github.com/NFUNM024/tupian/blob/master/%E8%A7%86%E9%A2%91%E5%BD%95%E5%88%B6%201.mp4)
