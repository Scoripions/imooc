# imooc
Imooc Git学习
Git

	什么是Git?
		Git(读音为/gɪt/。)是一个开源的分布式版本控制系统，可以有效、高速的处理从很小到非常大的项目版本管理。 Git 是 Linus Torvalds 为了帮助管理 Linux 内核开发而开发的一个开放源码的版本控制软件。
		Torvalds 开始着手开发 Git 是为了作为一种过渡方案来替代 BitKeeper，后者之前一直是 Linux 内核开发人员在全球使用的主要源代码工具。开放源码社区中的有些人觉得BitKeeper 的许可证并不适合开放源码社区的工作，因此 Torvalds 决定着手研究许可证更为灵活的版本控制系统。尽管最初Git的开发是为了辅助Linux内核开发的过程，但是我们已经发现在很多其他自由软件项目中也使用了 Git。例如 很多 Freedesktop 的项目迁移到了 Git 上
	为什么使用Git?
		1.牛逼的互联网，大神都在使用
		2.完整的版本控制，解决多人协作的问题
		3.提高开发的效率
	Git的两种使用：命令行、图形化界面（sourceTree）
		配置用户名和邮箱：
		git config --global user.name "xxx"
		git config --global user.email "xxx@xxx.com"
		初始化版本库：
		git init
		添加文件到版本库
		git add
		git commit
		查看仓库状态
		git status
		Git工作流：
			工作区--> 暂存区 --> 版本库
		初始化：
			git init --> git add --> git commit
		远程仓库：
			git remote add --> git pull --> git push --> git clone
		分支管理：
			git branch --> git checkout --> git merge
		标签管理：
			ggit tag --> git push
笔记在更新...
