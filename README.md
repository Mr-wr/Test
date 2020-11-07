# git 常用命令

## 提交代码

> 1、git add (文件名/\*/.)
> 2、git commit -m "说明"
> 3、git pull [origin(默认是主分支时可以不用写)]
> 4、git push 推送/上传 [origin(默认是主分支时可以不用写)]

## 合并分支

> 1、git checkout [name]//切换到其他分支
> 2、git merge [要合并分支的名字]

## git 设置忽略提交文件

> 1、添加.gitignore 文件
> 2、里面添加要忽略提交的文件
> 例如：

```java
//添加文件夹
test/
//添加文件
test.txt
```
