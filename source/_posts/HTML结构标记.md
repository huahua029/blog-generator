---
title: HTML结构标记
date: 2018-09-1７ 18:07:49
tags:
---
之前学习的时候，基本都是用div完成的，感觉不是很好，所以把HTML5中的结构标记做一个梳理

####1.main标签
 <main>元素呈现了文档或应用的主体部分。主体部分由与文档直接相关，或者扩展于文档的中心主题、应用的主要功能部分的内容组成。这部分内容在文档中应当是独一无二的，不包含任何在一系列文档中重复的内容，比如侧边栏，导航栏链接，版权信息，网站logo，搜索框（除非搜索框作为文档的主要功能）。
![image.png](https://upload-images.jianshu.io/upload_images/7513933-174a3f2fb5803f0c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

####2.article标签
<article>元素表示文档、页面、应用或网站中的独立结构，其意在成为可独立分配的或可复用的结构，如在发布中，它可能是论坛帖子、杂志或新闻文章、博客、用户提交的评论、交互式组件，或者其他独立的内容项目。
比如，我们写一篇新闻，其里边依然可以包含header，section等....
![image.png](https://upload-images.jianshu.io/upload_images/7513933-63e90eb05690efdc.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
####3.section标签
<section>元素标示文档中的一个区域（或节），比如，内容中的一个专题组，一般来所会有包含一个标题。一般通过是否包含一个标题（h1-h6）作为子节点来辨识section。
**注意**
１．如果内容要分成几部分，就使用<article>
２．不要把section作为一个普通的容器使用，这本应该是div的用法。（还是需要慎重点）
![image.png](https://upload-images.jianshu.io/upload_images/7513933-b692d097adf166d6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
####4.nav标签
<nav>元素描绘一个含有多个超链接的区域，这个区域包含转到其他页面，或者页面内部其他部分的链接列表。注意，这个我们称之为导航条，但是比如<footer>元素就没有必要加入nav的链接列表。
![image.png](https://upload-images.jianshu.io/upload_images/7513933-4f0f13a8044d10e5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
####5.aside标签
<aside> 元素表示一个和其余页面内容几乎无关的部分，被认为是独立于该内容的一部分并且可以被单独的拆分出来而不会使整体受影响。其通常表现为侧边栏或者嵌入内容。
![image.png]之前学习的时候，基本都是用div完成的，感觉不是很好，所以把HTML5中的结构标记做一个梳理

####1.main标签
 <main>元素呈现了文档或应用的主体部分。主体部分由与文档直接相关，或者扩展于文档的中心主题、应用的主要功能部分的内容组成。这部分内容在文档中应当是独一无二的，不包含任何在一系列文档中重复的内容，比如侧边栏，导航栏链接，版权信息，网站logo，搜索框（除非搜索框作为文档的主要功能）。
![image.png](https://upload-images.jianshu.io/upload_images/7513933-174a3f2fb5803f0c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

####2.article标签
<article>元素表示文档、页面、应用或网站中的独立结构，其意在成为可独立分配的或可复用的结构，如在发布中，它可能是论坛帖子、杂志或新闻文章、博客、用户提交的评论、交互式组件，或者其他独立的内容项目。
比如，我们写一篇新闻，其里边依然可以包含header，section等....
![image.png](https://upload-images.jianshu.io/upload_images/7513933-63e90eb05690efdc.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
####3.section标签
<section>元素标示文档中的一个区域（或节），比如，内容中的一个专题组，一般来所会有包含一个标题。一般通过是否包含一个标题（h1-h6）作为子节点来辨识section。
**注意**
１．如果内容要分成几部分，就使用<article>
２．不要把section作为一个普通的容器使用，这本应该是div的用法。（还是需要慎重点）
![image.png](https://upload-images.jianshu.io/upload_images/7513933-b692d097adf166d6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
####4.nav标签
<nav>元素描绘一个含有多个超链接的区域，这个区域包含转到其他页面，或者页面内部其他部分的链接列表。注意，这个我们称之为导航条，但是比如<footer>元素就没有必要加入nav的链接列表。
![image.png](https://upload-images.jianshu.io/upload_images/7513933-4f0f13a8044d10e5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
####5.aside标签
<aside> 元素表示一个和其余页面内容几乎无关的部分，被认为是独立于该内容的一部分并且可以被单独的拆分出来而不会使整体受影响。其通常表现为侧边栏或者嵌入内容。
![image.png](https://upload-images.jianshu.io/upload_images/7513933-f1644d596eb39e6b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- - -
####6.header标签
<header>元素表示一组引导性的帮助，可能包含标题元素，也可以包含其他元素，像logo、分节头部、搜索表单等。就是一个页面的头部信息。
![image.png](https://upload-images.jianshu.io/upload_images/7513933-9629a4e4f34addd3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

####7.footer标签
<footer>元素表示最近一个章节内容或者根节点元素的**页脚**。一个页脚通常包含作者、版权数据、相关链接等信息。注意<footer>元素内的作者信息应包含在<address>元素中。
![image.png](https://upload-images.jianshu.io/upload_images/7513933-f85dff0b31dbc576.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
####8.hgroup标签
The HTML <hgroup> element represents a multi-level heading for a section of a document. It groups a set of <h1>–<h6> elements.
表示文档的多层次标题，包含h1-h6。就是标题多的时候采用。
![image.png](https://upload-images.jianshu.io/upload_images/7513933-1392dbb34a50ffc3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
####9.address标签
用来呈现联系方式、电话、地址、邮箱等内容；
![image.png](https://upload-images.jianshu.io/upload_images/7513933-379b2e9f0248d60f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
(https://upload-images.jianshu.io/upload_images/7513933-f1644d596eb39e6b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- - -
####6.header标签
<header>元素表示一组引导性的帮助，可能包含标题元素，也可以包含其他元素，像logo、分节头部、搜索表单等。就是一个页面的头部信息。
![image.png](https://upload-images.jianshu.io/upload_images/7513933-9629a4e4f34addd3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

####7.footer标签
<footer>元素表示最近一个章节内容或者根节点元素的**页脚**。一个页脚通常包含作者、版权数据、相关链接等信息。注意<footer>元素内的作者信息应包含在<address>元素中。
![image.png](https://upload-images.jianshu.io/upload_images/7513933-f85dff0b31dbc576.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
####8.hgroup标签
The HTML <hgroup> element represents a multi-level heading for a section of a document. It groups a set of <h1>–<h6> elements.
表示文档的多层次标题，包含h1-h6。就是标题多的时候采用。
![image.png](https://upload-images.jianshu.io/upload_images/7513933-1392dbb34a50ffc3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
####9.address标签
用来呈现联系方式、电话、地址、邮箱等内容；
![image.png](https://upload-images.jianshu.io/upload_images/7513933-379b2e9f0248d60f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
