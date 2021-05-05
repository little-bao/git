### git

> 作用: 整合,部署,管理项目

### git命令

```
git --version #查看git版本号
# 表示注释
q 结束
clear 清屏
exit 退出
```



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
   
   git add 文件名称 #一次往暂存区添加一个文件
   git add . #把所有文件都添加到暂存区
   
   git commit -m 解释说明 #把暂存区的文件添加到本地仓库
   
   git branch -M main
   
   git remote add origin git@github.com:baozi9530/git.git #把网络仓库的连接放进别名origin中
   
   git push -u origin main #把本地仓库推送给网络仓库
   
   ```

### 版本回退命令

```
git log #查看当前版本以及之前的所有版本

git reflog #查看仓库所有版本以及恢复记录

git reset --hard id #从仓库中恢复到操作空间

git checkout 文件名称 #把暂存区中的文件覆盖操作空间中的文件,不能断电
```



### 下载仓库

```
git clone git@github.com:baozi9530/git.git
```

