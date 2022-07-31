# styleGithub
测试github

1、新建仓库
（1）New repository

2、克隆仓库
（1）git clone [远程仓库地址别名] [远程仓库地址]
（2）git clone干三件事：a.完整下载远程仓库地址到本地
                       b.创建远程仓库origin地址别名
                       c.初始化仓库-->.git
 （3）所以，克隆前不需要git init进行初始化
 
 3、上传代码
 （1）git add .
      git add 文件名
      
 （2）git commit -m '记录信息'
      这个步骤，可能需要用户授权
      
  （3）git push 
      推送，有时git push origin master
      
4、邀请队员加入
（1）在GitHub网页选中仓库，找到Settings
（2）找到Collaborators，然后添加队员GitHub账号（Add collaborator），等待队员同意邀请，并授权。
（3）复制邀请链接发送给队员（Copy invite link），通知队员授权。
（4）队员同意授权（Accept invitation）
变成队员就可以推送到远程仓库成功：git push (origin master)

5、pull=fetch+merge
（1）pwd
查看当前目录
（2）cat 文件名
查看文件内容
（3）pull分成两步骤进行时（较为推荐）：git fetch [远程仓库地址别名][远程分支名]      git merge 远程仓库地址别名/远程分支名
（4）pull一步到位时：git pull [远程仓库地址别名][远程分支名]

6、另外
（1）新建分支：mkdir 分支名
（2）进入分支：cd 分支名
    
