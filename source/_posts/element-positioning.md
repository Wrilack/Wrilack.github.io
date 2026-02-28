---
title: element positioning
date: 2026-02-27 20:10:13
tags: [dp]
categories: [学习, dp]
---
<a href= "https://www.drissionpage.cn/browser_control/get_elements/sheet" style = " font-size:50px"><cite>#语法速查表</cite></a>

# 1.通过属性定位
e.g:`tab.ele(@id=)`

`tab.ele(tag:input@@style=@@value=)`

# 2.iframe定位
<iframe src="/2026/02/13/markdown/index.html" title="iframe的介绍" height="400" width="400"></iframe>

e.g: <br>
>frame = tab.get_frame(t:iframe);<br>
ele = frame.ele()

>frame = tab.eles(t:iframe)[];<br>

# 3.相对定位

# 4.shadow_root的元素定位
&ensp;先找到其父元素才能访问

>ele1.shadow_root("t: iframe")

# 5.xpath定位(兼容性最好)

>xpath= 'x: '<br>
> page.ele(xpath)

