# HTML入门笔记1

今天学习了html第一课，收获很多。
html是李爵士的发明创造，2017年他获得了图灵奖，获奖时间有点晚，个人觉得他早就该获奖。
## html的起手式:
~~~html
<!DOCTYPE html>
<!--文档类型-->
<html lang="en">
<!--可以改为zh-CN-->
<head>
  <meta charset="UTF-8">
  <!--文件字符编码，UTF-8适用于全人类的所有语言-->
  <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <!--禁用缩放，兼容手机，宽度跟设备宽度一样，默认的缩放比例是1倍，最小缩放比例等于1，最大缩放比例等于1，用户不准缩放-->
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <!--告诉IE使用最新内核-->
  <title>html 代码</title>
</head>
<body>

</body>      
</html>
~~~
## 常用表章节标签
~~~html
<!--标题-->
<h1>标题</h1>
<h2>标题</h2>
<h3>标题</h3>
<h4>标题</h4>
<h5>标题</h5>
<h6>标题</h6>

<!--章节-->
<section>章节</section>

<!--文章-->
<article>文章</article>

<!--段落-->
<p>段落</p>

<!--顶部内容，如顶部广告-->
<header>顶部内容</header>

<!--底部内容，如版权之类的&copy;-->
<footer>底部内容</footer>

<!--主要内容-->
<main>主要内容</main>

<!--旁支内容-->
<aside>旁支内容</aside>

<!--区域划分-->
<div>区域划分</div>
~~~

## 全局属性
所有标签都有的属性
1. class
~~~html
<div class="middle bordered"></div>
~~~
2. contenteditable 内容可以直接被编辑

3. hidden
使标签看不见

4. id
注意id和class的区别，不到万不得已不要使用id，因为不会报错。

5. style属性
是标签属性，不是CSS中的style,它比CSS中的style优先级高，但没有Js中的高。
~~~html
<header style="border: 15px solid pink">
~~~
6. tabindex
正数，可以连续（按顺序访问）可以不连续（非顺序访问）
0，最后访问
负数，tab不能访问 

7. title
显示完整的内容

## 常用的内容标签
* ol li 有序列表
* ul li 无顺序列表
* dl+dt+dd 描述列表
  ~~~html
  <dl>
      <dt>描述的对象</dt>
      <dd>描述的内容</dd>　
  ~~~
* pre  保留空格回车tab键，正常使用
* hr 分隔线
* br 换行
* em 强调 语气
* strong  强调 内容
* quote  行内引用
* blockquote  块引用（换行）
     
  
