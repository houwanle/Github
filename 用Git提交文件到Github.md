# git提交文件到github上操作步骤
1. 进入到本地仓库
2. 将要提交的文件/文件夹拷贝到本地仓库
3. git add 文件名
4. git commit -m "first commit"
5. 到github上对应仓库复制仓库的SSH地址
6. git remote add origin git@github.com:houwanle/java.git
7. git push -u origin master
8. yes

# 将github上创建的仓库与本地仓库关联并且以后能用git上传提交文件步骤
1. 首先在本地git仓库下创建一个与远程仓库名字对应的文件夹；
2. 然后在bash里面进入到该文件夹下用git init初始化
3. 在bash里面输入  git remote add origin 仓库ssh地址   将本地仓库与远程仓库关联
4. git clone 远程仓库ssh地址    将远程仓库克隆到本地仓库
5. 在本地仓库更改文件/文件夹
6. 完成后进入到与远程仓库对应的本地仓库文件夹下，在bash里面输入：
```  
git add .
git commit -m "first commit"
git remote add origin 远程仓库地址
git push -u origin master
```