---
title: 'Learning c language(1): dynamic memory management'
date: 2026-02-13 09:48:57
tags: [c]
categories: [学习, c语言]
---
# **一** 相关函数
1. `void* malloc(size_t byte)`: 开辟动态空间\
&emsp;e.g:`int* a = (int*)malloc(40)`
2. `void* calloc(size_t, num )`
3. `void* realloc(void* ptr, size_t byte )`:重新分配

