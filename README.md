# mat-hexo

## 这是什么？

这是[mat实验室](https://mat.csust.xyz/)的官方GitHub Pages主页的hexo源文件，我们通过这些文件用hexo渲染并部署GitHub Pages。

## 如何使用？

### 检查你的权限

首先，确保你拥有相关的权限，比如在此页面提交的权限。当然，你可以向这个repo进行pull requests，我们欢迎任何原创文章的pr，同时，我们也保留进行筛选并确认是否合并您pr的权力。

### clone这个库

当你完成了第一步，并确认想要继续发布页面时，你应该clone这个库到本地，或者fork一份到您的GitHub，以便于你在其基础上进行你想要的修改。

### 安装hexo环境

由于我们的GitHub Pages使用的是[hexo](https://hexo.io/zh-cn/)框架，为了在您的电脑上顺利部署，您需要安装hexo环境。这里您应当参考hexo项目的[官方文档](https://hexo.io/zh-cn/docs/index.html)，或者利用搜索引擎自行解决。

### 创建新页面

在配置好环境后，您应该使用`hexo n "<yourPageName>"`来创建页面，并用markdown编辑器来进行编辑。同时，您需要参考我们使用的主题[Anisina](https://github.com/Haojen/hexo-theme-Anisina)的头部要求来加入tags，作者，编辑日期等其他信息。**不符合要求的md文件将在审核中被我们查出，我们会要求您进行修改**。

Anisina的要求大致如下，但您应当参考其开源项目主页的最新要求来进行填写。

```markdown
---
layout: post
title: "Hola 2016"
subtitle: "hi, I'm haojen ma"
date: 2016-05-26 06:00
author: "Haojen Ma"
header-img: "img/post-default.jpg"
cdn: 'header-on'
tags:
	- Movies
	- Life
---
```

### 提交

如果您拥有对这个repo进行直接写的权限，您可以直接使用git向这个库提交您的页面，如果您没有相应权限，您应该尝试对这个库进行pull requests。

## 注意事项

以下所有的注意事项都是为了项目的可维护性。

### 提交记录

在您所提交的页面中，您**必须**填写完整且详实的提交记录（commit logs），**不要**多次提交重用一个提交描述，也不要在描述中插入无意义的话。另外，提交记录最好用**无歧义的**中文填写。

