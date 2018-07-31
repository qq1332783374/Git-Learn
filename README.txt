Git的一些常用的操作！
	添加用户：
		git config --global user.name "your GitHub username"
		git config --global user.email "email@example.com"
		
	查看添加的用户：
		git config -l
	
	创建Git仓库：
		git init
	
	添加文件或文件夹：
		git add filename.txt   //添加单个文件
		git add file1.txt file2.txt  //添加多个文件
	
	提交文件：
		git commit -m "add file "
	
	查看运行结果：
		git status
	
	连接远程仓库：
		git remote add origin git@github.com:qq1332783374/Git-Learn.git
	
	提交文件到远程仓库:
		git push -u origin master
	
	提交成功后，以后可以用这个方式来提交：
		git push origin master
		
	Delete Git File :
		git rm -r --cached file.txt
		git commit -m "delete file"
		git push -u origin master
	
	修改远程仓库地址：
	
	1)修改命令：
		git remote set-url origin YourChangeUrl
	  
	2)先删除，后添加
		git remote rm origin    //删除远程仓库地址
	    git remote add origin YourNewUrl   //添加新的远程仓库地址
	
	3）直接到git的文件夹下面修改 config 文件
	  
	克隆远程仓库（就是把远程仓库的内容下载到本地）:
		例如：git clone https://github.com/qq1332783374/Git-Learn
	
	
