# Git记录

准备工作:
 1.先去github.com网站完成注册 得到用户名密码shengliangdong/*******

 2.如果是window用户(暂时买不起苹果),下载msysgit(含模拟环境Cygwin和Git) 下载网址http://msysgit.github.io
 安装介绍，下一步，直到完成。(Git Bash/Git CMD/Git GUI)三个软件。根据爱好选择其中一个。


 Git部分

 在Git上已有一个testdong仓库。

 1.首先在本地新建一个文件夹 如gitdir/

 2.打开Git GUI应用。 使用CMD命令进入gitdir目录。  然后执行(创建新仓库版本控制)
   git init
   (这时gitdir文件夹中有一个.git的隐藏属性的文件夹)

 3.接着在输入命令。克隆版本:
   git clone https://github.com/shengliangdong/testdong

   完成后gitdir目录中会一个testdong文件夹带.git文件夹

 4.添加与提交文件,修改了文件或者添加文件
   git add *或者filename

 5.提交说明
   git commit -m "说明信息"

 6.推送改动
   git push origin master

   注意：(如果不在master这个分支需要切换回来) git checkout master
   查看分支git branch  名字前有*则为当前分支。
   查看远程分支git branch -a
   获取主干最新代码git pull
   删除本地分支git branch -d testname


 7.提示输入用户名和密码


 8.更新使用
   git pull