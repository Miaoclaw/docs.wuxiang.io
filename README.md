# 无相文档


## 目录


### 1. 已具备 HTML/CSS 相关经验

[1. 从 0 创建 ifanr 网站的客户端](./zh/GetStarted.md)
[2. 无相编辑器的使用](./zh/Editor.md)
[3. 选择器和取值器](./zh/WIP.md)
[4. 无相的控件文档](./zh/WIP.md)


### 2. 不具备 HTML/CSS 知识

[1. 从 0 创建 ifanr 网站的客户端](./zh/GetStarted.md)
[2. 如何使用 Chrome 开发者工具](./zh/WIP.md)
[3. HTML/CSS 简介](./zh/WIP.md)
[2. 无相编辑器的使用](./zh/Editor.md)
[4. 无相的选择器和取值器](./zh/WIP.md)
[5. 无相的控件文档](./zh/WIP.md)


## 常见问题


#### 如何知道一个网站是不是静态加载的？

最简单的办法：查看网页源代码，然后搜索你在网页里面看到的关键词，试试能不能搜索的到。比如你看到一个网站“iPhone XXX" 然后再源代码中搜索 iPhone 如果能看到对应的代码那么「无相」就可以提取出来。


#### 为什么明明正确的 CSS 规则，「无相」取不到数据

有两种可能

1. HTML 是动态加载的，比如你打开少数派的首页，虽然你能看到文章列表的样式，但是它的内容都是 AJAX 动态加载的，所以取不到数据。

2. User Agent 原因：适配网站时一定要选择正确的 UA，因为大部分网站都会针对 PC和手机版使用不同的模板，「无相」默认使用手机版的 UA，而你用 Chrome 开发者工具查看网页结构时一定不要忘了切换到 `移动模式` 后刷新。