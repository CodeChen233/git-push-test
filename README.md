* https://blog.csdn.net/u014135752/article/details/79951802
* 1、新建一个文件夹
* 2、git init 变成一个代码仓库
* 3、把项目复制进来
# 4、git add . 把项目添加进代码仓库
* 5、git status 查看状态
# 6、git commit -m "first commit"把代码提交到仓库并写注释
* 7、git remote add origin https://github.com/CodeChen233/git-push-test.git 要上传的地址（在这之前要关联ssh密钥）只要写一次
# 8、git push -u origin master （新建的远程仓库是空的要加-u）/ git push origin master\
------------------------------------------------------------------
# 项目修改后git add ./git commit -m "注释"/git push origin master