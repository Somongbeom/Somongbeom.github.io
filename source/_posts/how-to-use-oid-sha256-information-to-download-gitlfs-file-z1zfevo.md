---
title: Git 如何使用 oid sha256 信息下载 git-lfs 文件
date: '2025-01-03 22:25:42'
updated: '2025-01-03 22:27:12'
tags:
  - git
categories:
  - 小知识
permalink: /post/how-to-use-oid-sha256-information-to-download-gitlfs-file-z1zfevo.html
comments: true
toc: true
---

# Git 如何使用 oid sha256 信息下载 git-lfs 文件

## 方案一

1、在自己的github右上角头像下找到一级目录settings，然后从二级目录中找到Packages，里面有一个Inherit access from source repository，将其选中并保存，这里的意思是表明从源项目中继承他的包，也就是项目中所有的链接中所对应的文件！  
2、保存后，再将原项目fork到你的仓库内，之后在你的仓库中打开这个项目，下载文件。

‍
