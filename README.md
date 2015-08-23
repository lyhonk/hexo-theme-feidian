# hexo-them-feidian
================
feidian是基于litten制作主题[hexo-theme-yilia](http://litten.github.io/2014/08/31/hexo-theme-yilia/)修改而来的。致谢[litten](http://litten.github.io/)

适用于 [hexo 2.4+](https://github.com/tommy351/hexo)
非常喜欢这款主题，崇尚简约优雅，在原作者为了追求简介性没有添加搜索框，我感觉有些不方便，所以给添加了一个使用[swiftype](http://www.swiftype.com/)的搜索功能，具体效果可以到[我的博客](http://feidian.click/)查看。           
 
如遇到问题或有需求，可以：
* 提issue给我
* 在这篇文章下留言[Hexo主题feidian](http://feidian.click/2015/08/23/hexo-them-feidian/)


我都会看到并处理。

如果你想体验手机浏览效果，可以扫一下二维码：

![feidaincode](http://feidian.click/blogimg/feidianerweima.png)

—————————————————————

# 关于主题：

1. 没有搜索感觉不方便，把添加了搜索框  
2. 修复原主题的多说bug
3. 添加文章目录功能   
4. 添加404页面
5. swiftype适用与2.0版本
6. 原主题用instagram作为相册，但是instagram被墙，目前不能适用

# 一、近期更新

2015.8.23 - 添加搜索和目录

# 二、使用

## 安装

``` bash
$ git clone https://github.com/lyhonk/hexo-theme-feidian.git themes/feidian
```

## 配置

修改hexo根目录下的 `_config.yml` ： `theme: feidian`

## 更新

``` bash
cd themes/feidian
git pull
```

#  三、外观

## **宽屏**
![宽屏](http://feidian.click/blogimg/kuang.png)        

## **窄屏**
![窄屏](http://feidian.click/blogimg/zhai.png)     

# 四、配置

主题配置文件在主目录下的`_config.yml`：

```
# Header
menu:
  Home: /
  All: /archives
  Monologue: /tags/Monologue
# Album: /tags/Album
  Tech: /tags/Tech

# SubNav
subnav:
  github: "https://github.com/lyhonk/"
  weibo: "http://weibo.com/jimmyccj/"
  mail: "mailto://Jimmy_ccj@outlook.com"
  #douban: "#"
  #mail: "#"
  #facebook: "#"
  #google: "#"
  #twitter: "#"
  #linkedin: "#"

rss: /atom.xml

# Content
excerpt_link: more
fancybox: true
mathjax: true

# 是否开启动画效果
animate: true

# 是否在新窗口打开链接
open_in_new: false

# Miscellaneous
google_analytics: ''
favicon: /favicon.png

#你的头像url
avatar: /avatar.jpg
#是否开启分享
share: true
#是否开启多说评论，填写你在多说申请的项目名称 duoshuo: duoshuo-key
#若使用disqus，请在博客config文件中填写disqus_shortname，并关闭多说评论
duoshuo: true
#多说的shortname
duoshuo_shortname: lyhonk
#是否开启云标签
tagcloud: true

#是否开启友情链接
#不开启——
friends: false
#开启——
#friends:
#  奥巴马的博客: http://localhost:4000/

#不开启——
#aboutme: false
#开启——
aboutme: You don't know me, I'm nobody, I'm everywhere, I always beside you. 

#是否开启swift搜索
swift_search:
  enable: true

```
# 五、其他

swiftype.com的代码请粘贴到**主题**目录中的source/js/swift.js文件中
