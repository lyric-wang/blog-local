---
title: "如何用hugo搭建个人博客"
date: 2019-08-31T21:29:23+08:00
lastmod: 2019-08-31T21:29:23+08:00
draft: false
tags: ["footnote", "markdown", "tag-11"]
categories: ["docs", "index"]
author: "LyricWang"
---

今天在饥人谷学习了如何用hugo搭建个人博客，下面是笔记

# 第一步：安装hugo，将路径添加到path

# 第二步：参阅hugo官方文档

* 进入[Hugo](https://gohugo.io/)官网，点击QuickStart，从第二步开始照做到第七步
* 第七步做完得到一个public目录，这就是我们的博客站点
* hugo server -D可以预览草稿，hugo server可以预览非草稿

# 第三步：预览网站

* 双击打开index.html发现不能预览，因为其不能使用文件协议预览
* 用hugo server预览

#第四步：用Github Pages让别人看到我们的博客

* 首先创建一个github repo，仓库名为github用户名.github.io
* 在本地的public目录创建本地仓库，并与刚创建的远程仓库关联
* 打开x.github.io的Github Pages