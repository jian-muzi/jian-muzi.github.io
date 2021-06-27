---
title: html锚点
date: 2021-06-26 15:02:14
tags: html
---
## 锚点就是在html文档标记一个位置，点击锚点链接就可以让滚动条移动到锚点标记的位置

### 当前页面锚点

 1.设置锚点标记

``` html
  <a name="anchor">这是一个锚点标记</a>
```

 2.设置锚点链接

``` html
  <a href="#anchor">点击我跳到anchor锚点标记</a>
```

### 跨页面锚点

1.设置锚点标记

``` html
<a name="anchor">这是一个锚点标记</a>
```

2.设置锚点链接

``` html
<a href="需要跳转的页面url#anchor">点击我跳到指定页面的anchor锚点标记</a>
```
