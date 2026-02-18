---
title: 'Learning c language (3): Random file read and write'
date: 2026-02-16 10:26:52
tags: [c]
categories: [学习, c语言]
---
# 1. sscanf 和 sprintf `(const char* s, const char* format, ***)`
&emsp;本质上是对***格式化数据***和***字符串***的转换

<mark>非针对文件流</mark>

# 2. 文件的随机读写
1. fseek: 改变文件流读写位置
2. ftell: 获取当前读写位置
3. rewind: 回到文件初始位置