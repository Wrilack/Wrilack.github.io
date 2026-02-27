---
title: element positioning
date: 2026-02-27 20:10:13
tags: [dp]
categories: [学习, dp]
---
# 1.通过属性定位
e.g:`tab.ele(@id=)`

`tab.ele(tag:input@@style=@@value=)`

# 2.iframe定位
<iframe src="/2026/02/13/markdown/index.html" title="iframe的介绍" height="400" width="400"></iframe>

e.g: <br>
>frame = tab.get_frame(t:iframe);<br>
ele = frame.ele()

>frame = tab.eles(t:iframe)[];<br>



