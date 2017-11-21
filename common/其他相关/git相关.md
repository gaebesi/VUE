# VUE
Vue商城项目

## git 操作
## 1.克隆gitHub项目到本地

```
git clone https://github.com/gaebesi/VUE.git .

后面加 . 代表省去克隆下来的文件夹的根目录
```

## 2.把自己的项目推送到gitHub仓库;

```
    git init #把仓库初始化
    git status #查看本地 文件有那些需要提交 如果不需要 忽略文件
        .gitignore
        .idea
    git add . #把本地文件添加到仓库
    git commit -am"本次提交的注释"
    git remote add origin https://github.com/gaebesi/VUE.git  #给本地仓库加上远程地址
    git remote -v  #查看本地仓库的远程地址
    git push origin master # 把提交后的代码推送到远程仓库  master分支名 自己取
```

## 3. 更新本地仓库代码
```
    有其他的分支
    git pull origin master
    没有其他分支
    git pull 
```

## 4. 本地代码切换分支
```
    git pull origin 分支名(更新某一个分支的代码)
    git fetch origin 
    git checkout 分支名(切换的分支)
```




