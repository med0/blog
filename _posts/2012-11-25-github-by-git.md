---
layout: post
title: 通过git简单地操作github
---
自从在github上搭建博客后，便需要通过git更新博客。以下几个简单地命令/操作可以通过git操作github，实现博客内容的修改和更新。

1. **云端克隆**：运行：git clone https://github.com/med0/blog.git；

1. **修改更新**：在/_posts文件夹中添加或者修改相应文章(文件)；

1. **更新本地git**：运行：git add .  及  git commit -m "your commit"；

1. **提交云端**：git push origin gh-pages。

通过以上4步，可以完成blog修改和更新的99%任务了。
