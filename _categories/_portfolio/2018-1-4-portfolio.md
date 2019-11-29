---
layout: article
title:  "markdown语法笔记"
date:   2018-01-04 22:07:50 +0800
categories: markdown_down
image:
  teaser: mdhead.jpg
  feature: md.jpg
---
markdown语法使用笔记
<div class="row img-rounded" style="background-color:#ffe4c4;padding:30px; box-shadow: 10px 10px 5px #888888; border: 1px solid #EA1D2D;">
<div class="col-md-12">
<div class="col-md-12"  markdown="1" >

## 引用（Reference）

一般应用于多个不同位置使用相同链接。通常分为两个部分：

调用部分格式为：[链接文本][ref]

注：两个中括号之间可以有空格。

定义部分可以出现在文本中的其他位置，格式为：[ref]: http://some/link/address (可选的标题)。

注：ref 中不区分大小写。


## 添加图片（Images）

添加图片的使用方法基本上和链接类似，只是在中括号前加叹号!，即
```
![Image Title](URL "Image Title")
```


## 文字引用（Blockquotes）


```
可以多级引用。

> Quote 1
> > Quote 2
> > > Quote 3
```

```
想在列表项里面使用区块引用，定界符>必须得缩进：

* Item
  > Quote 1
  > Quote 2
```


##  表格（Tables）

```
| Tables | Are | Cool  |
| ------ |:---:| -----:|
| col 3 is | right-aligned | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |

```
效果:

| Tables | Are | Cool  |
| ------ |:---:| -----:|
| col 3 is | right-aligned | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |

## 任务列表

```
- [x] [links](), **formatting**, and ~~tags~~ supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

```
效果：

- [x] [links](), **formatting**, and ~~tags~~ supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

 </div>
 </div>
 </div>

 
 

 
**作者：莫名其妙的WSM
链接：https://www.jianshu.com/p/bb1c4fb0fbc4
來源：简书
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。**


