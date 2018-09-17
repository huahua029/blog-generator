---
title: HTML概述
date: 2018-09-1６ 18:07:49
tags:
---
目录：
１．W3C简介
２．MDN简介
３．HTML所有标签列表（含部分解释）
４．空标签
５．可替换标签
６．其他

###１．W3C简介
W3C（万维网联盟），听名字就是一个机构，details是在web技术领域最具权威和影响力的国际中立性技术标准机构。比如给超文本标记语言（HTML）制定标准。为什么要制定标准呢？因为浏览器有很多，常见的chrome opera firefox safari ie等，要是这几家都自己玩自己的，那么问题就非常多了。所以，W3C制定标准，大家都采用这个标准，世界就简单了许多。

###２．MDN是什么
我们这里说的MDN（Mozilla Developer NetWork. Mozilla Developer Center），指的是MDN Web Docs，看名字就是“MDN 网络文档”，实际上是汇集众多Mozilla基金会产品和**网络技术开发文档**的免费网站。既然是免费＋文档，我们当然可以在MDN多查阅所需要的东西～

###３．HTML所有标签列表
* <!--..-->    定义注释
* <!DOCTYPE>    定义文档类型
* <a>　定义超链接
* <abbr>  定义缩写
* <address>　　定义地址元素
* <area>　　定义图像映射中的区域
* <article>　　定义article
* <aside>　　定义页面内容之外的内容
* <audio>　　定义声音内容
* <b>　　定义粗体文本
*<base>　　定义页面所有链接的基准URL
* <bdo> 　　定义文本显示的方向
* <blockquote>　　定义长的引用
* <body>　　定义body元素
* \<br\> 　　插入换行符
* <button>　　插入按钮
* <canvas>　　定义图形
* <caption>　　定义表格标题
* <cite>　　定义引用
* <code>　　定义计算机代码文本
* <col>    　　定义表格列的属性
* <colgroup>　　定义表格列的分组
* <command>  定义命令按钮
* <datalist>　　定义下拉列表
* <dd>　　定义　定义的描述
* <del>　　定义删除文本
* <details>　　定义元素的细节
* <dfn>　　定义　定义项目
* <div>　　定义文档中的一部分
* <dl>　　定义　定义列表
* <dt>　　定义　定义的项目
* <em>　　定义强调文本
* <embed>　　定义外部交互内容或插件
* <fieldset>　　定义fieldset
* <figcaption>　定义figure元素的标题
* <figure>　　定义媒介内容的分组以及它们的标题
* <footer>　　定义section或page的页脚
* <form>　　定义表单
* <h1>to<h6>　　定义标题１到标题６
* <head>　　定义文档的信息
* <header>　　定义section或page的页眉
* <hgroup>　　定义有关文档中的section的信息
* <html> 　　定义html文档
* <i>　　定义斜体文本
* <iframe>　　定义行内的子窗口
* <img>　　定义图像
* <input>　　定义输入
* <ins> 　　定义插入文本
*<keygen>　　定义生成密钥
* <kdb>　　定义键盘内容
* <lable>　定义表单控件的标注
* <legend>　　定义fieldset（自定义字段）的标题
* <li> 　　定义列表的项目
* <link>　　定义资源引用
* <map>　　定义图像的映射
* <mark>　　定义有记号的文本
* <menu>　　定义菜单列表
* <meta>　　定义元信息
* <meter>　　定义预定义范围内的度量
* <nav>　　定义导航链接
* <noscript>　　定义noscript部分
* <object>　　定义嵌入对象
* <ol>　　定义有序列表
* <optgrounp>　　定义选项组
* <option>　　定义下拉列表中的选项
* <output>　　定义输出的一些类型
* <p>　　定义段落
* <param>　　为对象定义参数
* <pre>　　定义预格式化文本
* <progress>　　定义任何类型的任务进度
* <q>  　　定义短的引用
* <rp>　　定义若浏览器不支持ruby元素显示的内容
* <rt>　　定义ruby注释的解释
* <ruby>　　定义ruby注释
* <samp>　　定义样本计算机代码
* <script>　　定义脚本
* <section>　定义section
* <select>　　定义可选列表
* <small>　　定义小号文本
* <source>　　定义媒介源
* <span>　　定义文档中的section
* <strong>　　定义强调文本
* <style>　　定义样式定义
* \<sub\>　　定义下标文本
* <summary>　　定义details（细节）元素的标题
* \<sup\>　　定义上标文本

###４.空元素
一个空元素可能是HTML，SVG，MathML里的一个不可能存在子节点的元素
*MathML元素，是数学标记语言，用来书写数学符号和公示的标记语言，对应的标签是<math>...</math>*
在HTML中，通常在一个空元素上使用闭合标签是无效的,
    
    <input type="text"></input>　闭合标签是无效的HTML
有以下空元素：<area> <base> \<br> <col> <colgroup> <command> <embed> \<hr> <img> <input> <keygen> <link> <meta> <param> <source> <track> <wrb>

###５．可替换元素（很不熟悉，见下一篇博客）
###６．其他（不太熟悉或者遗忘的）

* 制作电子邮件的链接：<a href="mailto:xxx@yyy">
* 在新窗口打开链接：<a href="url" target="_blank">
* 单元格内容左对齐：<td align="left">
* input的type属性:button\checkbox\file\hidden\image\password\radio\reset\submit\text
* 下拉列表：<select> ；文本区：<textarea>
*<colgroup>标签补充：用于对表格中的列进行组合，以便进行格式化，可以向整个列应用样式。只能在<table>元素之内，而且在任何一个<caption>（说明）元素之后，在<thead> <tbody> <tfoot> <tr>元素之前使用。若要在某列定义不同的属性，使用<col>。示例如下：
![image.png](https://upload-images.jianshu.io/upload_images/7513933-c889b05ff4b775d5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
结果如下：

![image.png](https://upload-images.jianshu.io/upload_images/7513933-3de618cb9bb59078.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- - - 
占坑～