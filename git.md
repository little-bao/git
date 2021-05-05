### git

> 作用: 整合,部署,管理项目



![git](F:\git\git.png)

### git命令

1. 第一次使用git时要先进行配置--必须设置

   配置用户名和邮箱,告诉仓库你是谁

   ```
   git config --global user.name "zero"
   
   git config --global user.email "zero@qq.com"
   
   (git config --list可查看)
   ```

   

2. 使用git管理本地项目

   ```
   git init #把文件夹初始化为本地仓库
   
git status #观察哪些文件没有放入暂存区
   
git commit -m 解释说明 #把暂存区的文件添加到本地仓库
   
   git branch -M main
   
   git remote add origin git@github.com:baozi9530/git.git #把网络仓库的连接放进别名origin中
   
   git push -u origin main #把本地仓库推送给网络仓库
   ```
   
   
   
   

