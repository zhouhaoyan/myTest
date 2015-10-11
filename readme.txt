
http://blog.jobbole.com/78960/ 教程

git初始化
git config --global usr.name "zhouhaoyan"

git config --global user.email "ttzhyran@163.com"

git 代码仓库建立

git init 

git add 文件名

git commit  -m "提交的注释内容"

git status        查看存在未提交   

git log   查看日志

git reset --hard HEAD^  版本会退到上一个版本  ^代表一个版本

git reset --hard HEAD~100   会退到前100个版本 

git reflog 查看版本号历史

git reset  –hard 6fcfc89 通过版本号恢复

ssh-keygen  -t rsa –C "youremail@example.com"  生成SSH key

git remote add origin https://github.com/zhouhaoyan/myTest.git 在本地库中执行该命令

git push origin master  提交到github 版本库

git clone https://github.com/zhouhaoyan/myTest.git  克隆版本库到本地