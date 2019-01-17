# HowToBuildUnityWithAndroid
unity+androidEnviroment
/*贴两个安装教程：
 *https://blog.csdn.net/u011926026/article/details/70339642?locationNum=11&fps=1
 *https://blog.csdn.net/dxj467822057/article/details/80198165

首先，下载Unity并安装，c盘够大就装c，勾选上ios和android选项。然后开始下载安装。
搭建android环境：
1，现在sun官网下载JDK。JDK文件是.exe结尾的，最新的就好。在C盘建立目录；要记住这个目录。像C:\Program Files\Java\jdk1.8.0_201。安装完成后配置环境，添加JAVA_HOME：C:\Program Files\Java\jdk1.8.0_201(安装目录)，Path:(最后加上)%JAVA_HOME%\bin（或者）还有%JAVA_HOME%\jre\bin(必要时加上分号分隔)。windows+r:cmd>java -version检验安装是否成功。
/*SDK是包含JRE的
 *下载JDK的网址：http://www.oracle.com/technetwork/java/javase/downloads/index.html.
 *注意下载的是java sdk而不是orcale sdk额。
 *文件名（根据与机型64代表64位机，86代表32位机）：jdk-11.0.2_windows-x64_bin.exe
 
2,入手安卓：分别下载android studio和android sdk。
下载网站(不可翻墙选择)：http://www.androiddevtools.cn/
安装android studio的时候只安装andriod studio（不用安装安卓模拟器），然后解压android sdk到E:\SDK\android目录下 .最后打开SDK manager即可,下载组件。



