---
title: Vim配置
date: 2024.01.26
updated: 2024.01.26
tags: 
  - Linux
  - 环境搭建
categories: Linux
cover:
highlight_shrink: false
toc: true
toc_number: true
toc_style_simple: true
mathjax: false
katex: false
---

# Vim配置

## VimPlus

[chxuan/vimplus: :rocket:An automatic configuration program for vim (github.com)](https://github.com/chxuan/vimplus)

### 禁用插件

` ~/.vimrc.custom.plugins`

```shell
UnPlug 'chxuan/cpp-mode'
UnPlug 'chxuan/vim-edit'
UnPlug 'chxuan/vimplus-startify'
UnPlug 'preservim/tagbar'
UnPlug 'Valloric/YouCompleteMe'
```

### 修改配置

`~/.vimrc.custom.config`

```shell
" 开启鼠标
set mouse=a

" 设置光标所在列高亮
set cursorcolumn

" indentLine 开启代码对齐线
let g:indentLine_enabled = 1
```



## 新增插件

### 高亮

**[vim-interestingwords](https://github.com/lfv89/vim-interestingwords)**

```shell
Plug 'lfv89/vim-interestingwords'
```

- `<Leader>k`：高亮，重复按取消高亮

### 下划线

```shell
Plug 'itchyny/vim-cursorword'
```

## 用法

- `<Leader>n`：开/关资源管理器
- `<Leader>k`：开/关当前关键词高亮
- `<Leader>g`：git提交记录
- `F9`：上一个主题
- `F10`：下一个主题
- `gcc`： 注释当前行
- `gcap`： 注释段落





