---
layout: post
title:  "HTML概览"
date:   2015-09-23 16:51:07
author: "蓝空鹰翔"
categories: tech
---

# 什么是HTML？
超文本标记语言 ，即HTML（Hypertext Markup Language），是用于描述网页文档的一种标记语言。

这种文本中含有超链接，可以将不同内存空间上的文本信息组织在一起。

##1.标签分类

1. 文档标签：`<html>`、`<head>`、`<body>`、`<title>`、`<meta>`、`<base>`、`<style>`、`<link>`、`<script>`、`<noscript>` 

2. 框架标签：`<frame>`、`<frameset>`、`<iframe>`、`<noframes>`

3. 布局标签：`<div>`

4. 表格标签：`<table>`、`<thead>`、`<tbody>`、`<tfoot>`、`<tr>`、`<td>`、`<th>`、`<col>`、`<colgroup>`、`<caption>`

5. 表单标签：`<from>`、`<input>`、`<textarea>`、`<button>`、`<select>`、`<optgroup>`、`<option>`、`<label>`、`<fieldset>`、`<legend>`

6. 列表标签：`<ul>`、`<ol>`、`<li>`、`<dl>`、`<dt>`、`<dd>`

7. 链接标签：`<a>`

8. 多媒体标签：`<img>`、`<map>`、`<area>`、`<object>`、`<param>`

9. 文章标签：`<h1>-<h6>`、`<p>`、`<br>`、`<span>`、`<abbr>`、`<blockquote>`、`<q>`、`<ins>`、`<del>`、`<address>`

10. 字体样式标签：`<tt>`、`<i>`、`<b>`、`<big>`、`<small>`、`<em>`、`<strong>`

11. 特殊标签：`<!DOCTYPE>`、`<!-- -->`、`<hr>`

##2.需要注意的标签讲解

1. 当文档中使用了`<frameset>`标签和`<body>`标签是互斥的，两者不能同时使用生效。

2. `<ul>`无序列表（unordered list），`<ol>`有序列表（ordered list）,`<li>`列表项（list item），`<dl>`定义列表（definition list）,`<dt>`定义项，（definition term）；`<dd>`定义描述，（definition description）。

3. 以下元素均是字体样式元素。`<tt>` `<i>` `<b>` `<big>` `<small>` 标签，以下元素都是短语元素`<em>` `<strong>` `<dfn>` `<code>` `<samp>`标签。

4. `<label>` 与`<input>`一般成对出现。`<label>`标签中的**for**属性可把 label 绑定到另外一个元素。请把**for**属性的值设置为相关元素的 id 属性的值。

##3.框架标签

1. HTML `<frameset>` 标签：frameset 元素仅仅会规定在框架集中存在多少列或多少行，必须使用 cols 或 rows 属性。

2. `<frameset>``</frameset>` 标签不能与 `<body>``</body>` 标签一起使用。

3. HTML `<iframe>` 标签：iframe 元素会创建包含另外一个文档的内联框架（即行内框架）。

4. HTML `<noframes>` 标签：noframes 元素可为那些不支持框架的浏览器显示文本。noframes 元素位于frameset 元素内部。

##4.表格标签

1. HTML `<table>` 标签：`<table>` 标签定义 HTML 表格。简单的 HTML 表格由 table 元素以及一个或多个 tr、th 或 td 元素组成。

2. **tr** 元素定义表格行，**th** 元素定义表头，**td** 元素定义表格单元。

3. HTML `<td>` 标签：`<td>` 标签定义 HTML 表格中的标准单元格。

4. HTML 表格有两类单元格：表头单元 - 包含头部信息（由 th 元素创建），标准单元 - 包含数据（由 td 元素创建）。

5. HTML `<thead>` 元素、 `<tbody>` 元素 、 `<tfoot>` 元素应结合起来使用。

#5.表单标签

1. HTML `<form>` 标签：`<form>` 标签用于为用户输入创建 HTML 表单。表单能够包含 `input` 元素，比如文本字段、复选框、单选框、提交按钮等等。表单还可以包含 `menus`、`textarea`、`fieldset`、`legend` 和 `label` 元素。表单用于向服务器传输数据。

2. HTML `<textarea>` 标签：定义多行的文本输入控件。

3. HTML `<button>` 标签：定义一个按钮。

4. HTML `<select>` 标签：可创建单选或多选菜单。

5. HTML `<option>` 标签： 元素定义下拉列表中的一个选项（一个条目）。

6. HTML `<optgroup>` 标签：定义选项组。当使用一个长的选项列表时，对相关的选项进行组合会使处理更加容易，配合 select 标签使用。

7. HTML `<label>` 标签：`<label>` 标签为 `input` 元素定义标注（标记）。由于浏览器的兼容性不同，所呈现效果不同，因而样式可自定义，保持在各个浏览器显示一样的效果。

##6.列表标签
1. HTML `<ul>` 标签

    `<ul>` 标签定义无序列表：

        <ul>
                <li>苹果</li>
                <li>梨</li>
        </ul>

2. HTML `<ol>` 标签

    `<ol>` 标签定义有序序列表：

        <ol>
                <li>第一名</li>
                <li>第二名</li>
        <ol>

3. HTML `<dl>` 标签

    `<dl>` 标签定义列表（definition list）：

        <dl>
            <dt>计算机</dt>
            <dd>用来计算的仪器</dd>
        </dl>
        <dl>
            <dt>显示器</dt>
            <dd>以视觉方式显示信息的装置</dd>
        </dl>
    
##7.字体样式标签

1. HTML `<b>`标签：呈现粗体文本效果。

2. HTML `<big>`标签：呈现大号字体效果。

3. HTML `<strong>`标签：把文本定义为语气更强的强调的内容。和 `<em>` 标签一样，用于强调文本，但它强调的程度更强一些。

4. HTML `<em>`标签：把文本定义为强调的内容。告诉浏览器把其中的文本表示为强调的内容。对于所有浏览器来说，这意味着要把这段文字用斜体来显示。

5. HTML `<small>`标签：呈现小号字体效果。

6. HTML `<i>`标签：显示斜体文本效果。

# 什么是HTML5？
HTML5 将成为 HTML、XHTML 以及 HTML DOM 的新标准。

HTML5 仍处于完善之中。然而，大部分现代浏览器已经具备了某些 HTML5 支持。

##1.HTML5有什么新特性？

1.用于绘画的 `canvas` 元素

2.用于媒介回放的 `video` 和 `audio` 元素

3.对本地离线存储的更好的支持

4.新的特殊内容元素，比如 `article`、`footer`、`header`、`nav`、`section`

5.新的表单控件，比如 `calendar`、`date`、`time`、`email`、`url`、`search`

##2.HTML5新增标签分类

1.结构标签：`<article>`、`<header>`、`<nav>`、`<section>`、`<aside>`、`<hgroup>`、`<figure>`、`<figcaption>`、`<footer>`、`<dialog>`

2.多媒体交互标签：`<video>`、`<audio>`、`<source>`、`<canvas>`、`<embed>`

3.Web应用标签：`<menu>`、`<menuitem>`、`<command>`、`<meter>`、`<progress>`、`<datalist>`、`<details>`

4.注释标签：`<ruby>`、`<rp>`、`<rt>`

5.其他标签：`<keygen>`、`<mark>`、`<output>`

6.重新定义的HTML标签：`<b>`、`<i>`、`<dd>`、`<dt>`、`<hr>`、`<menu>`、`<small>`、`<strong>`

##3.HTML5结构标签

1.`<article>`标签：标记定义一篇文章

    `<article>` 标签定义文章：

        <article>
            <h2>上学歌</h2>
            <p>
                太阳当空照，<br />
                花儿对我笑，<br />
                小鸟说早早早，你为什么背上小书包?<br />
                我要炸学校老师不知道，一拉线，赶快跑，<br />
                轰的一声，学校炸没了。<br />
            </p>
        </article>

2.`<header>`标签：标记定义一个页面或一个区域的头部

    <header>
        <p>这是一个header标签</p>
            <nav>
                <ul>
                    <li>首页</li>
                    <li>起夜</li>
                    <li>论坛</li>
                    <li>商城</li>
                    <li>社区</li>
                </ul>
            </nav>
    </header>

3.`<nav>`标签：标记定义导航链接

4.`<section>`标签：标记定义一个区域

5.`<aside>`标签：标记定义页面内容部分的侧边栏

6.`<hgroup>`标签：标记定义文件中一个区块的相关信息

7.`<figure>`标签：标记定义一组媒体内容以及它们的标题

    `<dialog>` 标签定义对话，比如交谈：

        <figure>
            <figcaption>UFO</figcaption>
            <p>不明飞行物 Unknown Flying Object</p>
        </figure>
        <figure>
            <dt>DDS</dt>
            <dd>大屌丝</dd>
        </figure>

8.`<figcaption>`标签：标签定义 figure 元素的标题

9.`<footer>`标签：标记定义一个页面或一个区域的底部

10.`<dialog>`标签：标记定义一个对话框(会话框)类似微信

    `<dialog>` 标签定义对话，比如交谈：

        <dialog>
             <dt>唐僧:悟空，你又调皮了，观音姐姐的月光宝盒怎么能乱扔呢？</dt>
             <dd>悟空:...(看着)</dd>
             <dt>唐僧:乱扔是不对的，砸到小朋友怎么办？就算砸不到小朋友，砸到花花草草也是不好的嘛</dt>
             <dd>悟空:...(纠结)</dd>
             <dt>唐僧:悟空你想要么？想要你就告诉我呀，你不告诉我怎么知道你想要呢？。。。。</dt>
             <dd>悟空:我靠!(一棍子抡上去！)</dd>
        </dialog>

##4.HTML5多媒体交互标签

1.`<video>`标签：标记定义一个视频

2.`<audio>`标签：标记定义音频内容

3.`<source>`标签：标记定义媒体资源

4.`<canvas>` 标签：标记定义图片

5.`<embed>`标签：标记定义外部的可交互的内容或插件，比如flash

##5.HTML5Web应用标签

1.`<menu>`标签：命令列表

2.`<menuitem>`标签：menu命令列表标签 FF（嵌入系统）

3.`<command>`标签： menu标记定义一个命令按钮

4.`<meter>`标签：状态标签(实时状态显示:气压、气温)

5.`<progress>`标签：状态标签 (任务过程:安装、加载)

6.`<datalist>` 标签：为input标记定义一个下拉列表

7.`<details>` 标签：标记定义一个元素的详细内容

##6.HTML5Web注释标签

1.`<ruby>`标签：标记定义 注释或音标

2.`<rp>` 标签：告诉那些不支持 Ruby元素的浏览器如何去显示

3.`<rt>` 标签：标记定义对ruby的注释内容文本

##7.HTML5其他标签

1.`<keygen>`标签：标记定义表单里一个生成的键值(加密信息传送)

2.`<mark>`标签：标记定义有标记的文本 (黄色选中状态)

3.`<output>` 标签：标记定义一些输出类型,计算表单结果配合oninput事

##8.HTML5重新定义的HTML标签

1.`<b>`标签：代表内联文本，通常是粗体，没有传递表示重要的意思

2.`<i>`标签：代表内联文本，通常是斜体，没有传递表示重要的意思

3.`<dd>`标签：可以同details与figure一同使用，定义包含文本，dialog也可用

4.`<dt>`标签：可以同details与figure一同使用，汇总细节，dialog也可用

5.`<hr>`标签：表示主题结束，而不是水平线，虽然显示相同

6.`<menu>`标签：重新定义用户界面的菜单，配合commond或者menuitem使用

7.`<small>`标签：表示小字体，例如打印注释或者法律条款

8.`<strong>`标签：表示重要性而不是强调符号
