# HowToBuildUnityWithAndroid
unity+androidEnviroment
/*贴两个安装教程：
 *https://blog.csdn.net/u011926026/article/details/70339642?locationNum=11&fps=1
 *https://blog.csdn.net/dxj467822057/article/details/80198165

首先，下载Unity并安装，c盘够大就装c，勾选上ios和android选项。然后开始下载安装。
搭建android环境：
1，现在sun官网下载JDK。JDK文件是.exe结尾的，最新的就好。在其他盘建立文件目录；像E:SDK/JAVA。安装完成后配置环境，添加JAVA_HOME：E:SDK/JAVA(安装目录)，Path:(最后加上)%JAVA_HOME%\bin还有%JAVA_HOME%\jre\bin(必要时加上分号分隔)。windows+r:cmd>java -version检验安装是否成功。
/*SDK是包含JRE的。
 *下载JDK的网址：http://www.oracle.com/technetwork/java/javase/downloads/index.html 
 *文件名（根据与机型64代表64位机，86代表32位机）：jdk-11.0.2_windows-x64_bin.exe
 
2,入手安卓：先下载安卓的SDK，即Android-SDk Tools。在E:SDK/下建立新文件夹Android。下载网站()不可翻墙选择)：http://www.androiddevtools.cn/
下载文件(往下翻到SDK Tools)下载文件：android-sdk_r24.4.1-windows.zip。下好后解压到E:SDK/Android/中


