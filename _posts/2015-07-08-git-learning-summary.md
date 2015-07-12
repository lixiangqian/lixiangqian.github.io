---
title: Comments on Git learning
layout: post
tag:
    - Git
    - Github
    - Syntax
categories: 编程
---

1: “git push”都提示要输入用户名和密码 [<i class="fa fa-link"></i>](https://help.github.com/articles/changing-a-remote-s-url/ "Changing a remote's URL")
>git remote -v //显示当前远端url

>git remote origin -set url git@github.com:username/username.github.io.git

2: "git push"时提示"waring: push.default is unset;"
>git config --global push.default.matching //未指定情况下推送所有分支<br>

改成：

>git config --global push.default.simple//未指定情况下推送当前分支

3: Git short status flag to see your changes in a more compact way

>git status -s

4: To see what you’ve changed but not yet staged

>git diff

5: Compares your staged changes to your last commit

>git diff --staged(or --cached)

6: Git-diff extra usage(will diff per platform)

>git difftool --tool-help

<pre class="md">
'git difftool --tool=<tool>' may be set to one of the following:
                vimdiff
                vimdiff2

The following tools are valid, but not currently available:
                araxis
                bc3
                codecompare
                deltawalker
                diffmerge
                diffuse
                ecmerge
                emerge
                gvimdiff
                gvimdiff2
                kdiff3
                kompare
                meld
                opendiff
                p4merge
                tkdiff
                xxdiff
</pre>
