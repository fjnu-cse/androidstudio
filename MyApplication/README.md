# 实验一 - HelloWorld

## 一、Android Studio的安装

1、Android Studio官网下载安装：

[https://developer.android.google.cn/studio/ ](https://developer.android.google.cn/studio/)

2、这里选择的是版本是：

![androidstudio_version](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/version.png)

## 二、创建第一个Android项目

1、双击打开前面已经安装好的Android Studio编译器

2、选择Start a new Android Studio project，然后Next

![start_project](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/start.png)

3、在Choose your project 页选择Empty Activity，然后Next

![empty_activity](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/empty.png)

4、在Configure your project 页填写该project的”Name“为”HelloWorld“，Package name默认，Save location为项目保存的位置，自定义。Language这里的选的Java，然后Finish。

![figure](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/figure.png)

5、创建成功后打开可以在左侧栏看到项目整体目录结构：

![construction](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/construction.png)

6、在run第一个project前，要File--->settings,配置基本环境。例如sdk的下载安装，virtual device的选择，自定义编译器背景等....

![construction](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/sdk.png)

![edit_title](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/Piex.png)

![construction](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/background.png)



7、编译运行第一个项目，File--->Sync with File System, 开始加载资源编译运行。由于电脑性能配置不是很好，花了较多时间。后面使用本地的gradle后时间有所缩短。而且，第一次运行编译发现了一些bug，后面各种debug后，run successfully。

![edit_title](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/hello.png)

## 三、自定义HelloWorld

1、自定义Title

![edit_title](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/title.png)

2、自定义Content

![edit_content](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/content.png)

## 四、Git的下载安装

1、直接去Git官网下载安装即可：

[https://git-scm.com/](https://git-scm.com/)

## 五、使用Git将本地项目资源打包上传到Github远程仓库

（Tip：从本地上传文件到github的前提是，已经注册一个github账户，并且账户里已经创建用于存放项目的仓库）

在github上的新建仓库后的应该看到：

![edit_title](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/newreposi.png)

1、在项目文件的上一层目录，右键目录文件，选择用Git-Bash打开。

2、在弹出来的命令行窗口依次执行以下命令（在github上新建仓库后也有相应命令行的提示）：

（1）git init 

![git_init](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/init.png)

（2）git config --global user.name 'your username'

![construction](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/username.png)

（3）git config --global user.email 'your email'

![git_init](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/email.png)

（4）git add dest(你的项目文件名，这里是MyAppLication)

![add](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/add.png)

（5）git commit -m 'brief introduction for your program'(备注)

![git_init](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/commit.png)

（6）git branch -M master

![git_init](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/branch.png)

（7）git remote add origin https://......(github上的仓库地址)

![git_init](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/remote.png)

（8）git push -u origin master

![git_init](https://github.com/ly-datas/androidstudio/tree/master/MyApplication/pics/push.png)

3、项目上传成功后，github上创新页面，会看到仓库中多了前面上传好的项目。

## 六、总结

​		第一次实验，熟悉了Android Studio的一些基本操作，能够创建一个Android项目并且成功运行项目；同时，也了解到了Git的一些基本用法，掌握了将本地git仓库上的资源上传到github远程仓库的基本步骤。
