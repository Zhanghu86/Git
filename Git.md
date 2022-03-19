###Git工具

https://git-scm.com/download/win 下载对应版本安装

修改环境变量，将git写进去

git --version	//查看git版本

gitgutter	//这个插件做本地变化提示

常用命令

git init	//初始化仓库

git status//第一次查看，显示的是没有被跟踪的文件				

git status -s	//-s 查看简要的文件信息

git add .	//可以将一个没有被跟踪的文件添加到跟踪列表

			//代码库添加一个 .gitignore 记录不被跟踪的文件夹

git commit -m '第一次提交代码到仓库'	//将本地的仓库归档

git log		// 查看提交日志

git reset --hard 2d2250  //回滚到某个版本【2d2250】

#

git branch	//查看分支

git branch v2	//复制分支

git checkout v2  //切换版本分支

git clone github仓库网址

git branch gh-pages

git checkout gh-pages

git push -u origin gh-pages 


###github是个网站，存储代码的仓库。

git remote add origin github仓库网址	//设置远端地址		

git push -u origin master	//将本地的源码同步到远端仓库  

git pull origin master

git remote -v	//

###Gist

存放代码片段。


git分支

SourceTree
