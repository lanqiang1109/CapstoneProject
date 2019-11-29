---
layout: article
title:  "此模版网站笔记"
date:   2018-01-05 22:07:50 +0800
categories: webnote 
image:
  teaser: web.jpg
  feature: webin.jpg
---
## 概要
网站学习过程中的笔记分享，例如如何在此模版上加入文章等。

<div class="row img-rounded" style="padding:30px; box-shadow: 10px 10px 5px #888888; border: 1px solid #D19F2A;">
<div class="col-md-12">
<div style="background: #D19F2A; color:white; border-radius:6px; padding:6px;"  markdown="1">
#### 如何po文章上首页
</div>
<div class="col-md-8" markdown="1" >
找到源模版文件夹里的_posts文件夹，里面含有数个以"年-月-日-jekyll_文章名"的markdown文件。
用Nopepad+++打开即可修改文章内容，想增加文章就以相同的命名格式建立一个markdown文件，在上面的添加基本信息。
首页文章的排序会根据一定规则排序，本模版以基本信息中的date标记，从最近日期开始排序文章。
文章内容放在div内才容易控制排版，否则默认左对齐。
基本信息中的<img src="./images/imgex.jpg"  style="width: auto">将会选择在首页显示的图片。
在想要加图片的地方添加代码<img src="./images/imgadd.jpg"  style="width: auto">就可以显示预备的图片，
注意images文件夹与所编写的.md文档需在同一个文件夹内。
</div>


</div>
<div style="background: #D19F2A; color:white; border-radius:6px; padding:6px;"  markdown="1">
#### 如何将Tabelau工作簿po上自己的网页
</div>
<div class="col-md-8" markdown="1" ><!-- right -->
首先要创建自己的Tabelau账号，上传自己的工作簿到Tabelau服务器中

* 打开Tabelau服务器中自己的工作簿，点击下方分享，然后复制出现的分享代码。

* 在自己url的文件夹里创建index.md文档，接着创建基本的网页代码 <img src="./images/1.jpg">
* 然后在body部分里面粘贴复制得到的分享代码
 
* 用此方式做出来的Tabelau分享图表会遵循默认左对齐原则，所以整体工作簿会偏左。

* 最简捷的解决方法为在复制出来的分享代码里的div中的style后面加上margin: 0 auto；整个div代码一般为<img src="./images/2.jpg">，这样就可以使得工作表居中。

* 如有多项Tabelau工作簿需要分享，则在第一个div后继续添加分享代码即可。

</div>
</div>
