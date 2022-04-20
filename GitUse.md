# Git Use

	合并分支：
	A和B两个人写一个项目，A现在要合并代码
	
	A：
	(A branch	A在自己的分支上)
	git add .
	git commit -m "A commit"
	git push
	
	(切换到main分支上)
	git checkout main
	git pull
	git merge A
	
	(这时候可能会有冲突 就是main上面的代码和A的代码有不一样的地方)
	git status   (查看所有的冲突文件名字)
	/或者使用
	git diff     (查看一个？)
	
	(现在知道了哪里有冲突，就要打开文件来编辑代码
	一般有冲突的地方 打开软件后都是会显示的
	然后就在软件里编辑冲突的地方)
	
	？？？待续
