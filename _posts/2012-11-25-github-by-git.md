---
layout: post
title: 通过git简单地操作github
---

自从在github上搭建博客后，便需要通过git更新博客。以下几个简单的命令/操作可以通过git操作github，实现博客内容的修改和更新:

- 云端克隆： 运行如下：

{% highlight r %}
git clone https://github.com/med0/blog.git
{% endhighlight %}



- 修改更新：  在/_posts/文件夹中添加或者修改相应文章(文件)；


- 更新本地git：  运行如下：

{% highlight r %}
git add .
git commit -m "new blog"
{% endhighlight %}

- 提交云端： 运行如下：

{% highlight r %}
git push origin gh-pages
{% endhighlight %}

通过以上4步，可以完成github上blog修改和更新的99%任务了。
