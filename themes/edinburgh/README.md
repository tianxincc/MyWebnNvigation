# 模板说明

## 框架

模板基于bootstrap封装的一个简单的响应式模板，源代码地址：https://sharvaridesai.github.io/hexo-theme-edinburgh-demo/

##　结构说明

名称及地址结构
edinburgh：模板文件夹
themes\edinburgh\layout：主要文件夹，样式调整及页面设计全部在此文件夹的文件中修改
themes\edinburgh\layout\_partial： 页面框架，上、下、左、右 设计底层样式模板

themes\edinburgh\layout\_partial\footer.ejs ： js相关引用
themes\edinburgh\layout\_partial\google-analytics.ejs ：google-analytics 暂未使用，忽略
themes\edinburgh\layout\_partial\head.ejs ：页面头部区域设计底层样式模板
themes\edinburgh\layout\_partial\header.ejs ： 菜单栏的底层设计模板themes\edinburgh\layout\_partial\page-full.ejspage-full： 菜单栏点击进入后页面相关内容样式模板
themes\edinburgh\layout\_partial\portfolio-full.ejs : 关联首页点击进入后的页面相关内容样式模板
themes\edinburgh\layout\_partial\portfolio-index.ejs ： 主页面核心区域的样式

themes\edinburgh\layout\index.ejs ：首页内容区域，关联portfolio-index.ejs
themes\edinburgh\layout\layout.ejs ：
themes\edinburgh\layout\page.ejs
themes\edinburgh\layout\post.ejs

themes\edinburgh\source：　资源文件，img、css、js、icon 等文件放于此处
