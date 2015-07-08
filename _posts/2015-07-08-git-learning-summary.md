---
title: 学习Git的小心思小总结
layout: post
tag:
    - Git
    - Github
    - Syntax
categories: 编程
---

**1. 每次“Git Push”都提示要输入用户名和密码**
{% highlight %}
git remote -v //查看当前远端分支
git remote origin -set url git@github.com:username/username.github.io//设置远端分支为git@github.com形式，取代原来的https://github.com
{% endhighlight %}
