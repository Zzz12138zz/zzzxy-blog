---
title: "基于Hugo部署Blog站点"
subtitle: ""
date: 2026-01-15T12:55:36+08:00
lastmod: 2026-01-15T12:55:36+08:00
draft: false
authors: [Zzz]
description: ""

tags: []
categories: []
series: [基于Hugo部署自己的博客]

hiddenFromHomePage: false
hiddenFromSearch: false

featuredImage: "cover.webp"
featuredImagePreview: "cover.webp"

toc:
  enable: true
math:
  enable: true
lightgallery: true
license: ""
headless: false
---
本站使用Hugo项目，搭配DoIt主题，部署而成。该文将记录一些注意事项和常用命令。
<!--more-->
{{< admonition tip "为什么要拥有一个属于自己的博客？" true>}}
它将帮助建立个人品牌，获得创作自由和尊重，享受快速、稳定的阅读体验，并完全掌控自己的数字资产，同时培养结构化写作和知识管理能力，记录学习轨迹。

- 一个内容优质、设计专业的个人博客，是你最好的技术名片，它将系统地展示你的专业知识、思考深度和持续学习能力。

- 写作是最高效的学习方式，通过博客整理所学，能让你对知识的理解更系统、更深刻，文档系统也是能帮助团队固化最佳实践。

{{< /admonition>}}

## Hugo
[Hugo](https://gohugo.io/)是最流行的开源静态站点生成器之一。凭借其惊人的速度和灵活性，Hugo使构建网站再次变得有趣。

它将所有内容预先生成为**静态 HTML 文件**。用户访问时，服务器直接发送这些文件，无需数据库查询或后端程序动态渲染。这意味着加载速度极快，对搜索引擎优化（SEO）和用户体验至关重要。

静态文件可以被部署在任何托管服务上（如 Netlify, Vercel, GitHub Pages，甚至对象存储），这些服务大多提供免费额度。无需购买昂贵的虚拟主机或担心服务器被攻击。

[更多信息见Hugo官方文档](https://gohugo.io/documentation/)

### 下载Hugo extended
{{< admonition tip "为什么需要extended版本？" true>}}
由于部分主题的一些特性需要更丰富的功能支持，推荐使用 Hugo **extended** 版本来获得更好的使用体验.
{{< /admonition>}}

[下载Hugo extended](https://github.com/gohugoio/hugo/releases)，请按照设备操作系统下载对应的版本。

> 例如：
> **Hugo版本**：`0.154.5`
> **操作系统**：`Windows`  
> 则选择 [hugo_extended_0.154.5_windows-amd64.zip](https://github.com/gohugoio/hugo/releases/download/v0.154.5/hugo_extended_0.154.5_windows-amd64.zip) 下载即可。  


---

## *未完待续……*
---
{{< admonition note "记录一些常用命令" true>}}
- **清理垃圾**：`hugo --gc`
- **启动服务**：`hugo server -D -e production --disableFastRender --dind localhost --port 8888`
{{< /admonition>}}

---

TODO