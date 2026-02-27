---
title: markdown
date: 2026-02-13 23:32:48
tags: [md]
categories: [学习, markdown]
---
# 1.iframe(html的一个元素)
iframe（内联框架）是HTML中的一个元素，用于在当前网页中嵌入另一个独立的HTML页面。它允许在主页面中创建一个子窗口，加载外部内容，如网页、视频、广告或文档。iframe的独立性使其成为实现内容隔离和跨域嵌入的常用工具。

- ## iframe的常见用途

iframe广泛应用于以下场景：

嵌入视频，如YouTube或Vimeo。

加载广告，确保广告内容与主页面隔离。

嵌入外部内容，如第三方应用或表单。

内嵌文档，如PDF或HTML文件。

实现跨域内容嵌入，但需注意安全限制。

iframe的核心属性

以下是iframe常用的属性及其功能：

`<iframe src="https://example.com" width="600" height="400" title="示例"></iframe>
`

src：指定嵌入页面的URL。

width和height：设置iframe的宽度和高度。

sandbox：限制iframe的权限，如禁止脚本执行或表单提交。

allow：控制iframe的特殊功能，如全屏或摄像头访问。

loading：设置加载方式（lazy延迟加载或eager立即加载）。