---
title: Hexo博客Latex
date: 2024.01.29
updated: 2024.01.29
tags: 博客
categories: 博客
cover: https://lulu-dt.oss-cn-chengdu.aliyuncs.com/markdown%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20240129110950.jpg
highlight_shrink: false
toc: true
toc_number: true
toc_style_simple: true
mathjax: true
katex: true
---

# Hexo博客Latex

> 🏎转载自：
>
> [hexo博客:butterfly主题解决无法显示Latex数学公式 | AIL'BLOG (gitee.io)](https://ling71.gitee.io/posts/1518592324.html)

## 渲染器

```shell
npm uninstall hexo-renderer-marked --save
npm install hexo-renderer-kramed --save
```

## 修改配置文件

```yaml
mathjax:
  enable: true
```

## 修改文章配置

```yaml
...
mathjax: true
...
```

## Try

```markdown
$$\begin{eqnarray} 
  \sigma(z) \equiv \frac{1}{1+e^{-z}}.
\end{eqnarray}$$
```

$$\begin{eqnarray} 
  \sigma(z) \equiv \frac{1}{1+e^{-z}}.
\end{eqnarray}$$



