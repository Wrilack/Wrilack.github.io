---
title: learning c language(4)
date: 2026-02-18 18:08:36
tags: [c]
categories: [学习, c语言]
---
<div style="text-align: center"># 一，文本文件和二进制文件</div>

1. 文本：以ascii形式储存（字符）
2. 二进制：以二进制储存（文本编辑器中可能乱码）

<div style="text-align: center"># 二，文件读取结束的判定</div>

1. `ferro`和`feof`用于当文件结束时，判断是**读取失败**还是**遇到文件末尾**。 符合则返回真。
2. 读取结束：文本
|文本   |二进制   |
|---|---|
|返回值为`eof/null`   |返回值等于要读元素个数   |


