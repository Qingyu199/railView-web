# railView-web

这是一个基于railView后端程序的一个前端优化项目，旨在将JavaFx的前端修改为基于VUE的前端代码，实现前端的优化。

# 安装步骤

## 第一步：准备
1.下载安装apache tomcat 9 （笔者下载的是9.0.76）
链接地址为：https://tomcat.apache.org/download-90.cgi
一般来说，windows用户请下载`64-bit Windows zip`。

![8e222e7c7d8f5d5116e240f33b66ca7](https://github.com/Qingyu199/railView-web/assets/30193452/66b7f88a-f45d-4884-a07f-cbdf74bb5d5e)


下载好后解压到一个没有中文和特殊字符的目录下，请记住目录位置，后续要使用。

2.安装eclipse
链接地址为：https://www.eclipse.org/downloads/

![1688755957839](https://github.com/Qingyu199/railView-web/assets/30193452/2cc380b7-e76f-4b34-9ccd-9e955858752e)


请按提示安装。

## 第二步：测试服务器
请打开apache tomcat 9的安装目录，进入bin，

![1688756129311](https://github.com/Qingyu199/railView-web/assets/30193452/1eb35718-d63e-40d3-b269-ec82fa395e80)


双击startup.bat文件，打开浏览器，输入地址：`localhost：8080`，

![1688756391715](https://github.com/Qingyu199/railView-web/assets/30193452/515ba179-d151-4e97-8522-71a3f3dff7ac)

如下图所示则是服务器正常运行。双击shutdown.bat可关闭服务器。

![image](https://github.com/Qingyu199/railView-web/assets/30193452/11ec70c8-bce5-40b0-9706-cfb767b0413d)

## 第三步：部署服务器
1.将本远程库下载到本地，使用git clone来完成`git clone https://github.com/Qingyu199/railView-web.git`。

2.使用eclipse打开该project，（打开时请注意使用javase1.8作为编译器，tomcat 9.0作为运行服务器版本）。

3.右键点击railView-web项目文件，选择`export`，选择`WAR file`

![image](https://github.com/Qingyu199/railView-web/assets/30193452/8b320dfe-6846-49da-b1a3-6b72941be465)

4.请按如下图填写war文件导出的选项，目标地址可以直接设置在apache tomcat 9目录下的webapps文件夹下

![image](https://github.com/Qingyu199/railView-web/assets/30193452/7e6f881a-45f3-489d-95d3-7fc18276b5e4)


5.双击startup.bat文件，打开浏览器，输入地址：`localhost：8080/railView-web`，就可以使用本程序了




