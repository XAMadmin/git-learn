# Git 入门学习

## git 的基本操作

1. 创建仓库：git init
2. 添加文件到仓库： git add README.md(提交单个文件)  git add -A(提交所有文件) 补充：（查看添加状态git status）
3. 提交仓库：git commit -m '提交说明'
4. 建立远程仓库连接：git remote add origin   （~加提交方式）
5. 上传远程仓库：git push -u origin master
6. 修改文件后再次提交执行2-3操作，最后git push
7. 拉取最新代码：git pull
8. git clone 克隆远程仓库代码



## ssh 密钥与添加用户

+ 生成密钥 ssh-keygen
+ C:\Users\Administrator\.ssh 公钥：id_rsa.public(复制到远程仓库配置) 密钥：id_rsa

## 添加.gitignore过滤上传文件

+ 常用过滤规则

```swift
/mtk/ 过滤整个文件夹
*.zip 过滤所有.zip文件
/mtk/do.c 过滤某个具体文件
```

```swift
!src/   不过滤该文件夹
!*.zip   不过滤所有.zip文件
!/mtk/do.c 不过滤该文件
```











































