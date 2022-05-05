# Hyper Text Markup Language



[w3c](http://www.chinaw3c.org)标准包括
- 结构化标准语言(HTML, XML)
- 表现标准语言(CSS)
- 行为标准语言(DOM, ECMAScript)


##

### 网页的基本结构

```html
<!-- DOCTYPE: 告诉浏览器我们使用的规范 -->
<!DOCTYPE html>
<html lang="en">

<!-- 网页的头部 -->

<head>
    <!-- 自闭合标签 -->
    <!-- 描述性标签 meta: 一般用来做SEO -->
    <meta charset="UTF-8">
    <meta name="keywords" content="学习网页">
    <meta name="description" content="用来学习html的网页">
    <!-- Title: 网页的标题 -->
    <title>Title</title>
</head>

<body>
    Hello World!
</body>

</html>
```



### 网页的基本标签

内容都写在`body`里

```html

<body>
    <!-- 标题标签 -->
    <h1> Head 1 </h1>
    <h2> Head 2 </h2>
    <h3> Head 3 </h3>
    <h4> Head 4 </h4>
    <h5> Head 5 </h5>
    <h6> Head 6 </h6>
    <!-- 段落标签 -->
    <p>段落</p>
    <!-- 换行标签 -->
    换行标签 <br />
    <!-- 水平线标签 -->
    <hr />
    <!-- 字体样式 -->
    <strong>粗体</strong>
    <em>斜体</em> <br />


    <!-- 注释和特殊符号 -->
    <!-- 空格 -->
    空&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;格
    <!-- 大于 -->
    &gt;
    <!-- 版权符号 -->
    &copy;
</body>

```


### 图像

```html
    <!-- 图片 -->
    <!-- alt: 图片加载不出来时候的文字 -->
    <img src="../resource/g1.jpg" alt="我是一个图片" title="悬停文字" />
```


### 链接

```html
<!-- link -->
    <!-- target: open in where -->
    <a href="https://www.baidu.com" target="_blank">
        <img src="../resource/g1.jpg" alt="我是一个图片" title="悬停文字" />
    </a>
    <a href="https://www.baidu.com" target="_self">
        百度
    </a>






    <!-- 锚链接 
    1. 需要一个标记
    2. 跳转到标记
    -->
    <!-- name: 标记 -->
    <a name="down">底部</a>

    <!-- 跳转 -->
    <a href="#down">到底部</a>
    <!-- 还可以组合使用 -->
    <!-- herf=url#down -->



    <!-- 邮件链接 -->

    <a href="mailto:zhigaowang@zju.edu.cn">联系我</a>


    <!-- QQ链接 -->
```



### 块元素和行元素

- 块元素: 无论内容多少，该元素独占一行
- 行元素: 内容撑开宽度，左右都是行内元素的可以排在一排

### 列表














