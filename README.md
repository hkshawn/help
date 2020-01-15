# github的使用帮助

#建立本地git仓库

git init

#将项目的所有文件添加到本地仓库中

git add .

#提交之前对本地仓库的修改

git commit -m 'first commit'

#git commit -m "注释语句"

#将本地的仓库关联到GitHub

git remote add origin git@github.com:hkshawn/help.git

#上传github之前pull一下

git pull origin master

#上传代码到GitHub的远程仓库

git push origin master
