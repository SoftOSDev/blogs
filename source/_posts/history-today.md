---
title: History Today 历史上的今天配置
date: 2025-09-13 10:30:24
tags: 
  - history
  - 开源
  - github
  - html
  - 嵌入
---

> History-Today 懒人版历史上的今天，只需添加上“id”就能使用

建议使用 **Chrome** 浏览器，体验最佳效果。

玩html的朋友们都知道，感觉自己的html总少些什么，现在给大家做了一个这个小玩意儿，可以直接嵌入在html里

## 1 简介

- 支持自定义样式css
- 只需要在你的\<p>或\<span>里加上id就可以了
- 无需占用本地空间，联网搜索

## 2 使用方法

用法：在你的<code>\<p\></code>或<code>\<span\></code>中加上id="tohis"
<hr>
示例：

<code>&lt;p id="tohis"&gt;&lt;/p&gt;</code>
   
   <hr>

   
<li> 在使用它之前，你需要引用js库：</li>

1. <code>&lt;script src="https://cdn.jsdelivr.net/gh/softosdev/history-today/tohis.js "&gt;&lt;/script&gt;</code>
2. <code>&lt;script src="https://softosdev.github.io/history-today/tohis.js "&gt;&lt;/script&gt;</code> (不推荐)

<li>或将 <a href="https://softosdev.github.io/history-today/tohis.js">tohis.js</a>下载</li>

<code>&lt;script src="scripts/tohis.js"&gt;&lt;/script&gt;</code>

<hr>
完整代码：<br><br>

~~~
<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <title>历史上的今天</title>
</head>

<body>
    <p id="tohis"></p>
    <script src="https://cdn.jsdelivr.net/gh/softosdev/history-today/tohis.js"></script>
</body>

</html>
~~~

## 3 嵌入示例

![image.png](https://wmimg.com/i/41/2025/09/68c4dad8de5cf.png)
  

