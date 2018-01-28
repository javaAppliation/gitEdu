# windows 下gitEdu
1. 安装git客户端
2. 应该是要配置下文件 ssh
# 流程
## 远程仓库克隆
1. 个人习惯：页面上new Repository 仓库就是代码的文件夹，然后clone下去. 
![aa](http://oydcisax6.bkt.clouddn.com/20180129003108_qLFJRW_Screenshot.jpeg)

2. 然后桌面上clone就是复制下来需要加url如下图
![aa](http://oydcisax6.bkt.clouddn.com/20180129003325_SbnZUq_Screenshot.jpeg)

3. 桌面命令行clone操作
![aa](http://oydcisax6.bkt.clouddn.com/20180129005152_cO1Jba_Screenshot.jpeg)

4. clone 完成之后就可以进行代码的修改编写。一个人的项目可以随便写，多人修改同一个项目的时候注意冲突。
## 本地仓库建立或者上传 宝宝都懒得这样用
1. mkdir 一个文件夹或者直接新建一个文件夹，cd 到这个目录里，然后git init 就可以了应该会生成.git 文件。不用管，以后就知道干嘛用的。啊啊啊，不写这个了。

# 常用命令 （目录得对）
```javascript 
git clone 
git status //修改代码之后查看哪些被修改到。
git add . // 点号代表通配哦 ，当然可以和通配符搭配。
git commit -m ' message'  //message 是注释。
// !!! 以上的操作都是在本地仓库进行的切记，接下来的操作是推送到托管代码的地方。
git pull origin master // pull 是优先拉去服务器上的代码之后再进行push 操作，这样可以一定成都减少冲突，因为先拉去了最新的代码。
git push origin master //推送代码到服务器上去。
// !!! origin master 是仓库默认branch 。 如果一个项目多个branch 的话，可以进行对branch 的选择。
git branch //查看分支
git checkout xx //就可以选择分支 然后git pull 拉取最新的代码
// 最后遇到冲突不要害怕 手动解决 idea 里可以清楚的看到...
```
# 工作原理
## 本地仓库
![aa](http://oydcisax6.bkt.clouddn.com/20180129011742_8wVExC_Screenshot.jpeg)
## 分支
![aa](http://oydcisax6.bkt.clouddn.com/20180129011842_tSp22s_Screenshot.jpeg)
## 大全
![aa](http://oydcisax6.bkt.clouddn.com/20180129013907_lFtDFP_gitflow.jpeg)






