  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
exercise1：
	git init：在进入文件夹后，用git init初始化
	git status：检查当前文件夹下文件的状态
		红色：未被管理（修改过或新增的）
		绿色：已经被管理（使用了git add 文件名提交的）
		未出现的：已经加入版本（被管理后且使用了 git commit -m '版本信息' 提交的）
	git add 文件名：将文件加入管理
	git commit -m '版本信息'：提交版本