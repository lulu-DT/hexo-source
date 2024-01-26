---
title: Butterfly Config
date: 2024.01.25
updated: 2024.01.26
tags: 博客
categories: 博客
cover: https://lulu-dt-images.oss-cn-chengdu.aliyuncs.com/images/journey/1.jpg
highlight_shrink: false
toc: true
toc_number: true
toc_style_simple: true
mathjax: false
katex: false
---



# Butterfly

参考自：

> 📚 索引
>
> 🚀 [快速开始](https://butterfly.js.org/posts/21cfbf15/) - 📑 [主题页面](https://butterfly.js.org/posts/dc584b87/) - 📌 [主题配置-1](https://butterfly.js.org/posts/4aa8abbe/) - ⚔️ [主题配置-2](https://butterfly.js.org/posts/ceeb73f/) - ❓ [主题问答](https://butterfly.js.org/posts/98d20436/) - ⚡️ [进阶教程](https://butterfly.js.org/posts/4073eda/)

## 配置

### 导航栏头像

```yaml
nav:
  logo: #image
  display_title: true
  fixed: false # fixed navigation bar
```

### 头像

```yaml
avatar:
  img: /img/avatar.png
  effect: true #头像转圈
```

### 顶部图片

[其它图片介绍](https://butterfly.js.org/posts/4aa8abbe/#%E9%A0%82%E9%83%A8%E5%9C%96)

```yaml
default_top_img：
```

### 菜单目录

```yaml
首页: / || fas fa-home
时间轴: /archives/ || fas fa-archive
标签: /tags/ || fas fa-tags
目录: /categories/ || fas fa-folder-open
清单||fas fa-list:
  音乐: /music/ || fas fa-music
  电影: /movies/ || fas fa-video
  照片: /Gallery/ || fas fa-images
友链: /link/ || fas fa-link
关于: /about/ || fas fa-heart
```

### 文章目录

[原文](https://butterfly.js.org/posts/4aa8abbe/#TOC)

```yaml
toc:
  post: true
  page: true
  number: true
  expand: false
  style_simple: false # for post
  scroll_percent: true
```

### 页面锚点

```yaml
# anchor
anchor:
  # when you scroll, the URL will update according to header id.
  auto_update: true
  # Click the headline to scroll and update the anchor
  click_to_scroll: false
```



### 文章打赏

[链接](https://butterfly.js.org/posts/4aa8abbe/#%E6%96%87%E7%AB%A0%E6%89%93%E8%B3%9E)

```yaml
reward:
  enable: true
  text:
  QR_code:
    - img: /img/wechat.jpg
      link:
      text: 微信
    - img: /img/alipay.jpg
      link:
      text: 支付宝
```

### 标签Plugin

[链接](https://butterfly.js.org/posts/4aa8abbe/#%E6%A8%99%E7%B1%A4%E5%A4%96%E6%8E%9B%EF%BC%88Tag-Plugins%EF%BC%89)

```markdown
{% note simple %}
默认 提示块标签
{% endnote %}

{% note default simple %}
default 提示块标签
{% endnote %}

{% note primary simple %}
primary 提示块标签
{% endnote %}

{% note success simple %}
success 提示块标签
{% endnote %}

{% note info simple %}
info 提示块标签
{% endnote %}

{% note warning simple %}
warning 提示块标签
{% endnote %}

{% note danger simple %}
danger 提示块标签
{% endnote %}

```

{% note simple %}
默认 提示块标签
{% endnote %}

{% note default simple %}
default 提示块标签
{% endnote %}

{% note primary simple %}
primary 提示块标签
{% endnote %}

{% note success simple %}
success 提示块标签
{% endnote %}

{% note info simple %}
info 提示块标签
{% endnote %}

{% note warning simple %}
warning 提示块标签
{% endnote %}

{% note danger simple %}
danger 提示块标签
{% endnote %}



