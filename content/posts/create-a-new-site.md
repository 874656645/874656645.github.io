---
title: "Create a New Site by Hugo"
date: 2018-12-14T22:40:04+08:00
draft: true
---

# 创建站点

## Step1：创建站点

进入到 E:/Hugo/Sites文件夹<br/>
`hugo new site HugoLearning.com` 

## Step2：添加样式主题
```
cd HugoLearning.com

git init

git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke
```
编辑 _config.toml_ 配置文件<br/>
最后一行添加 `theme = "ananke"`<br/>
或者 `echo 'theme = "ananke"' >> config.toml`<br/>

## Step3：添加markdown文件内容

`hugo new posts/Hello-Hugo.md`

## Step4: 启动网站

`hugo server -D` <br/>

然后输入网址 _http://localhost:1313/_


