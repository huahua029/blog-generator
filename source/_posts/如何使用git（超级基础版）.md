---
title: 命令行基础
date: 2018-09-13 18:07:49
tags:
---
###如何使用git（超级基础版）
####1.只在本地使用
**记清楚：**
    
    git init
    git add
    git commit 
第一步：在需要初始化的目录下输入命令 'git  init' ，会产生一个仓库 .git ，据说有毒，就不点开看了。
![image.png](https://upload-images.jianshu.io/upload_images/7513933-7f74447aecf54cf7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
这时候：我们可以用 'git status -sb' 看看我们刚才的那些文件
![image.png](https://upload-images.jianshu.io/upload_images/7513933-55051988059f3c8a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
提示的还挺明显的～

第二步：我们用 'git add' 将文件添加到所谓的暂存区（我也不知道在哪）比如我们将 '1.md' 添加进去
![image.png](https://upload-images.jianshu.io/upload_images/7513933-2e17ef5cb46d370a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
我们发现 1.md 前边由问号变为A，说明干成了。

第三步：我们就需要将刚才”暂存区“的文件提交到本地仓库！用' git commit -m ”信息“ '，我们将刚才的 1.md提交进去（这一步需要添加注释，省的忘）
![image.png](https://upload-images.jianshu.io/upload_images/7513933-dc58d32b435c8d0d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
会发现，已经提交走了～～～
**这时候**怎么看变动呢？利用 ’git log‘ 去看就可以
![image.png](https://upload-images.jianshu.io/upload_images/7513933-e48f58abc1f1c633.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
到此，如何在本地使用就说完～～～0.0不过文件变动怎么办，我还没看，也没遇到问题～先挖个坑～
####2.将本地仓库上传到github
####3.在github 上创建仓库，下载到本地