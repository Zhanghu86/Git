###Git工具

https://git-scm.com/download/win 下载对应版本安装

修改环境变量，将git写进去

#git常用命令

	git --version	//查看git版本

	git init	//初始化仓库

	git status	//第一次查看，显示的是没有被跟踪的文件				

	git status -s	//-s 查看简要的文件信息

	git add .	//可以将一个没有被跟踪的文件添加到跟踪列表

			//代码库添加一个 .gitignore 记录不被跟踪的文件夹

	git commit -m '第一次提交代码到仓库'	//将本地的仓库归档

	git log		// 查看提交日志

	git reset --hard 2d2250  //回滚到某个版本【2d2250】

	git remote add origin github仓库网址     //设置远端地址		

	git push -u origin master		//将本地的源码同步到远端仓库  

	git pull origin master			//讲远程仓库的源码更新到本地

	git remote -v				//查看远程仓库地址

	#

	git branch	//查看分支
	
	git branch <v2> //创建分支

	git checkout v2  //切换分支

	git clone <url>  //克隆分支
	


#上传的时候报错

	! [rejected] master -> master (non-fast-forward)
	error: failed to push some refs to

	1, git pull origin master

	2, git add .

	3, git commit -m

	4, git pull --rebase origin master

	5, git push -u origin master



#安装好环境的情况下运行Vue项目步骤

	###1.把远程仓库代码克隆到本地

	cd E:\Program Files\nodejs\testmall	

	###2.安装所需依赖

	cnpm install		

	###3.可以修改lib目录中interface.js文件中的的api地址		

	###4.启动项目

	npm run serve	


###composer

	https://www.phpcomposer.com/: 下载 setup.exe 安装程序即可
	
	全局配置  “path”—>打开“编辑系统环境变量”—“环境变量”

	composer self-update  
  
  

###安装好Redis的情况下

	1，在redis的目录下执行（执行后就作为windows服务了，开机自启动） 执行前 redis.windows.conf文件中 requirepass 123  设置auth密码

	redis-server --service-install redis.windows.conf

	2，安装好后需要手动启动redis

	redis-server --service-start

	3，停止服务

	redis-server --service-stop

	4，卸载redis服务

	redis-server --service-uninstall  

	常用命令

	redis-server -v

	redis-cli

	config get requirepass
