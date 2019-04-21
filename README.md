# 使用指南

## 设置

`_config.yml`



## 新页面创建

在根目录下创建`.md`文件，在文件开头设置新页面配置信息

```
layout: allposts
title: All posts
landing-title: 'All posts'
nav-menu: false
description: null
image: null
author: null
show_tile: false
```

`layout: allposts, home, page, post,...`

`title: title of page`

`landing-tilte (opt): title for display`

`nav-menu: if shown in nav bar manu`

`description (opt): the description shown in tile module`

`image: image for post and tile module`

`show_tile: if shown in tile module`

此文件支持html文件格式。



## 自定义修改的部分

### Menu

Hard code了AFMA主页链接在Menu中，参见`_includes/header.html`.

