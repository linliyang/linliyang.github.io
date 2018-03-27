---
title: Hello World
teaser: 一句话博客简介.
category: 类别标签
tags: [hello, first, demo]
---

`Mauris` 这是一个大标题
----------------------------------------

这里是第一个博客demo<dfn>词语强调</dfn> 

1. 第一个分点
2. 第二个有注释的分点.[^1] 

## 这是一个二级标题

有链接的demo唷 [带有超链接的点][kds] 

* Aenean eu quam nulla.
* Mauris vitae congue magna.
* <mark>做标记的区域</mark>.


### 这是一个三级标题
~~~
Curabitur quis
felis magna
代码区域
~~~

#### 这是一个四级标题 卡片式排版

这里添加一个可以跳转本地目录的超链接 [本地目录][nisi]:

> #### 卡片区域的标题
> 
> 这里是文本内容Et magna in erat gravida rhoncus a non sem. Vestibulum ante ipsum primis in
> faucibus orci luctus et ultrices posuere cubilia Curae; Curabitur dignissim:
>
> <b>强调字体:</b> `{% raw %}{{ "a eleifend dignissim" | risus }}{% endraw %}`
> 
> <b>强调字体:</b> `a-eleifend-dignissim`

---

[^1]:注释的解释内容
[kd]: http://kramdown.gettalong.org/
[rd]: https://github.com/davidfstr/rdiscount
[rc]: https://github.com/vmg/redcarpet
[kds]: https://github.com/linliyang
[nisi]: {% link _posts/2017-03-27-lorem-ipsum-dolor.md %}
