### docsify特点
* 属于静态博客的一种，相比动态博客搭建简单
* 依赖少，搭建过程不容易因为依赖问题阻塞

### 依赖
安装依赖npm工具，可以直接安装node.js获得

### 安装命令
1. 安装客户端
> npm install -g docsify-cli

2. 确定是否安装完成
> docsify -v

3. 初始化项目

> mkdir docsify-blog && cd docsify-blog
> docsify init

4. 启动项目
> docsify serve


### 部分配置的介绍
index.html下维护了docsify的配置信息
* 主题
> <link rel="stylesheet" href="//unpkg.com/docsify/lib/themes/vue.css">
共有五种常用主题vue.css、buble.css、dark.css、pure.css、dolphin.css

* 开启封面
> coverpage:true

* 开启导航
> loadNavbar:true

* 开启侧边栏
> loadSidebar: true

### 初始化模板
在安装docsify之后不想折腾配置文件可以直接拷贝以下模板：
[docsify-obsidian-template](https://github.com/Riaehtnipu/docsify-obsidian-template)
