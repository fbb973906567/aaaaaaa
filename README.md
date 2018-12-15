# git提交本地代码至github仓库的方法
* 1、生成本地项目文件
* 2、在github上生成仓库文件夹
* 3、将项目文件夹clone到本地
* 4、在本地，将之前的本地项目文件拖到刚刚clone下来的项目文件夹里
* 5、运行git指令

```js
git add --all   //将文件添加到仓库中
git commit -m "提交时候的自定义注释"   // 将需要添加的文件commit到仓库
git push    // 将commit的代码push到远程分支

```

# 第一次提交的时候，git遇到报错
 ```js
please  tell me who you are   

 ```
大概意思是我可能是第一次提交git，需要初始化name和email

查看name和email
```js
git config user.name
git config user.email
```

修改name和email
```js
git config --global user.name "your name"
git config --global user.email "your email"
```
