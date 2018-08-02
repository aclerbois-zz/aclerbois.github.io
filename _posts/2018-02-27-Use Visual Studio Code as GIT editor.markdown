---
layout: post
title:  "Use Visual Studio Code as GIT editor"
date:   2018-02-27 22:37:00
categories: VSCode
author: AClerbois
github_repo_username: aclerbois
github_repo : aclerbois
comments: true
---
By default, git is configured to use VIM as git editor, but you can configure your git environment to use Visual Studio Code.

![Git Loves VS Code](/images/ms_loves_git.png "Git Loves VS Code")
<!-- more -->
If you, like me want to use Visual Studio Code as the git editor, you should have Visual Studio Code install in a way that you can use it in command line, to try this open a command line and type the command « code ». If this command opens a new instance of Visual Studio Code you can continue the exercise on the other case, reinstall Visual Studio Code and check the option for command line.

To configure, go on a command line and type this command :

{% highlight c %}

git config --global --add core.editor "code --wait"

{% endhighlight %}

To test this functionality type the following command :

{% highlight c %}

git config --global -e

{% endhighlight %}
