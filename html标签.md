# HTML 常用标签大全

HTML 提供了丰富的标签用于构建网页结构和内容。以下是按照功能分类的最常用 HTML 标签：

## 1. 文档结构标签
- `<!DOCTYPE html>` - 声明 HTML5 文档类型
- `<html>` - HTML 文档的根元素
- `<head>` - 包含文档的元信息
- `<body>` - 包含文档的可见内容
- `<title>` - 定义浏览器标签页标题

## 2. 文本内容标签
- `<h1>` 到 `<h6>` - 标题标签（从最重要到最不重要）
- `<p>` - 段落
- `<br>` - 换行
- `<hr>` - 水平线
- `<span>` - 行内容器，用于样式化或脚本操作
- `<div>` - 块级容器，用于样式化或脚本操作

## 3. 格式化标签
- `<strong>` - 重要文本（加粗显示）
- `<em>` - 强调文本（斜体显示）
- `<b>` - 加粗文本（无语义）
- `<i>` - 斜体文本（无语义）
- `<u>` - 下划线文本
- `<sup>` - 上标文本
- `<sub>` - 下标文本

## 4. 列表标签
- `<ul>` - 无序列表
- `<ol>` - 有序列表
- `<li>` - 列表项
- `<dl>` - 定义列表
- `<dt>` - 定义术语
- `<dd>` - 定义描述

## 5. 链接与图像
- `<a>` - 超链接

- `<img>` - 图像

  - ```html
    <img
      src="img-400w.jpg"  <!-- 默认使用400px -->
      srcset="img-120w.jpg 120w, img-400w.jpg 400w"
      sizes="(max-width: 500px) 120px, 400px"
      alt="示例图片"
    >
    ```

    

- `<figure>` - 图像容器

- `<figcaption>` - 图像标题

## 6. 表格标签
- `<table>` - 表格
- `<tr>` - 表格行
- `<th>` - 表头单元格
- `<td>` - 表格数据单元格
- `<thead>` - 表头区域
- `<tbody>` - 表格主体
- `<tfoot>` - 表格页脚

## 7. 表单标签
- `<form>` - 表单容器
- `<input>` - 输入字段
- `<textarea>` - 多行文本输入
- `<button>` - 按钮
- `<select>` - 下拉列表
- `<option>` - 下拉列表选项
- `<label>` - 表单标签
- `<fieldset>` - 表单分组
- `<legend>` - 分组标题

## 8. 多媒体标签
- `<audio>` - 音频内容

  - ```html
    <audio controls>
        <source src='#' type='audio/mp3'>
        <source src="viper.ogg" type="audio/ogg" />
          <p>你的浏览器不支持该音频，可点击<a href="viper.mp3">此链接</a>收听</p>
    </audio>
    ```

    

- `<video>` - 视频内容

  - ```html
    <video src="#" controls>
        <p>
            后备内容，当浏览器不支持<video>元素时，显示这段内容
        </p>
    </video>
    
    <video controls muted poster preload>
        <source src='#1' type="video/mp4">
        <source src='#2' type="video/webm">
        <p>
            后备内容
        </p>
    </video>
    ```

    

- `<source>` - 多媒体资源

- `<track>` - 多媒体字幕

## 9. 语义化标签（HTML5新增）
- `<header>` - 页眉
- `<footer>` - 页脚
- `<nav>` - 导航栏
- `<section>` - 文档章节
- `<article>` - 独立内容
- `<aside>` - 侧边栏内容
- `<main>` - 文档主要内容
- `<time>` - 日期/时间

## 10. 其他常用标签
- `<meta>` - 元数据
- `<link>` - 外部资源链接
- `<script>` - JavaScript代码
- `<style>` - CSS样式
- `<iframe>` - 内嵌框架

这些标签构成了现代网页开发的基础，合理使用它们可以创建结构良好、语义清晰的网页。