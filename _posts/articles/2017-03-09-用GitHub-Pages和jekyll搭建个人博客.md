---
layout: post
title: "用GitHub-Pages和jekyll搭建个人博客"
categories: articles
excerpt:
tags: [网络技术]
comments: true
share: true
image:
  feature: so-simple-sample-image-4.jpg
date: 2017-03-09T15:39:55-04:00
modified: 2017-03-09T14:19:19-04:00
---

闲来无事，打算搭建个人博客。查阅了各种资料，发现目前最省钱省力的方法就是在 GitHub Pages 上利用 jekyll 静态网页生成器搭建。
对于 Web 开发小白来说，自己写网页代码不太现实。 好在GitHub 上有许多其他大神制作好的 jekyll 模板，直接 fork 过来修改一下就可以使用，其余的精力都可以用在文章内容本身上。

- - - - - - -

## 搭建步骤

1. 在 GitHub 上找到自己喜欢的 jekyll 模板， fork 到自己的仓库下，然后点击 Setting 修改仓库名称
2. 将 fork 后的项目 clone 至本地
3. 打开 _config.yml 文件修改其中的信息
4. 添加文章和博客到 _posts 文件夹
5. `git add .` 添加新增文件；`git commit -am "post update"` 提交修改；`git push` 推送更改到远端仓库
6. 以后每次更新文章后只需运行下面的命令即可更新网页：

```
git add .
git commit -am "post update
git push
```

- - - - - - -

本博客使用的主题为 *mmistakes* 的 [so-simple-theme](https://github.com/mmistakes/so-simple-theme) 主题
