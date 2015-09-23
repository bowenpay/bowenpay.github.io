---
layout: post
title:  "如何学习HTML:   2015-09-23 16:51:07
author: "蓝空鹰翔"
categories: tech
---

# 什么是HTML？
超文本标记语言 ，即HTML（Hypertext Markup Language），是用于描述网页文档的一种标记语言。

这种文本中含有超链接，可以将不同内存空间上的文本信息组织在一起。

##1.标签分类

1. 文档标签：`<html>`、`<head>`、`<body>`、`<title>`、`<meta>`、`<base>`、`<style>`、`<link>`、`<script>`、`<noscript>` **用户名** 。

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

6. HTML `<optgroup>` 标签：`<label>` 标签为 `input` 元素定义标注（标记）。由于浏览器的兼容性不同，所呈现效果不同，因而样式可自定义，保持在各个浏览器显示一样的效果。

##6.列表标签
1. HTML `<ul>` 标签

    `<ul>` 标签定义无序列表：

        <ul>
                <li>苹果</li>
                <li>梨</li>
        </ul>

1. HTML `<ol>` 标签

    `<ol>` 标签定义有序序列表：

        <ol>
                <li>第一名</li>
                <li>第二名</li>
        <ol>

1. HTML `<dl>` 标签

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