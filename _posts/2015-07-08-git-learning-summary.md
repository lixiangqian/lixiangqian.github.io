---
title: Comments on learning Git
layout: post
tag:
    - Git
    - Github
    - Syntax
categories: 编程
---

1. 1: “git push”都提示要输入用户名和密码 [<i class="fa fa-external-link"></i>](https://help.github.com/articles/changing-a-remote-s-url/ "Changing a remote's URL")
>git remote -v

>git remote origin -set url git@github.com:username/username.github.io.git

2. 2: "git push"时提示"waring: push.default is unset;"
>git config --global push.default.matching //未指定情况下推送所有分支<br>
改成：
>git config --global push.default.simple//未指定情况下推送当前分支

