---
layout: post
title: "工欲善其事必先利其器——Markdown"
date: 2017-04-08 18:54:47 +0800
categories: tools
---

## 写作工具利器——Markdown

> We believe that writing is about content, about what you want to say – not about fancy formatting.
>
>我们坚信写作写的是内容，所思所想，而不是花样格式。

上面是我们对写作的本质认识。但现实是我们总要依托一定的工具来进行写作，有所见即所得的（What you see is what you get）Windows 里的Microsoft Office，还有唐纳德老爷爷开发的LaTex: What you do is what you get哲学的写作工具。为了两种方式的兼顾，有了支持Latex实时显示效果的一些工具支持。

他们的缺点也显而易见，Windows Office写作时需要作者不断的调整格式，还有不同程度的程序崩溃可能性。Latex虽然语法犀利可以做到写作时用code指定排版，但是它海量高深的语法和各种环境搭建问题使得环境搭建和学习曲线非常的长。

于是Markdown横空出世——Markdown 是一种轻量级的「标记语言」，它实际上是个非常简单、非常容易学习的语法。这个语法简单到每个人都可以在5分钟以内学会。而且又有各种方式可以方便得转换为windows word，html，pdf等格式。可以认为Markdown是对一些复杂语言如LaTex等的又一次升华，就像编程语言一次次的推陈出新。

>[Markdown——入门指南](http://www.jianshu.com/p/1e402922ee32/)
>
>[Markdown中文版语法说明](http://wowubuntu.com/markdown/basic.html)
>
> [创始人 John Gruber 的 Markdown 语法说明](http://daringfireball.net/projects/markdown/syntax)

类似编程语言、HTML语言，你甚至可以在一个纯文本编辑器里用Markdown语法进行文章写作，在最终发表时使用其他工具转换为响应的目标文件格式即可。

说了这么多，Markdown对应的一些工具有什么可以支持我们写作？基本上现在主流的写作需求可以分为两类：

（1）一类是普通文档、图表等的基本需求

（2）一类是有图表、数学公式等的科技写作需求

在我用过的工具中，认为下面两个工具可以很好的满足已上两种需求。在工具选择时自然也考虑了跨平台问题，下面的两种工具对于跨平台支持：Windows、Mac、Linux都有很好的支持。

## 一，  普通文档写作利器：Markdown + Atom

Atom是github出品的IDE工具，经过几年的发展目前基本上可以和Sublime Text一较高下。但是由于他对于插件的管理感觉笔Sublime Text要方便人性许多，所以我现在基本上倾向于使用Atom。对于上文说的第一类需求普通文档写作和基本图表中的需求，使用Atom然后安装对应的插件即可。可以参考下下面的文章来进行Atom的安装与配置。

[使用Atom打造无懈可击的Markdown编辑器](http://www.cnblogs.com/fanzhidongyzby/p/6637084.html)

## 二， 科技文章写作利器：Markdown + R

在科技文章写作时最多用到的就是数学公式的展现了。对于这种情况LaTex是有自己的语法支持来搞定的，而Markdown的解决之道就是对LaTex公式语法进行兼容。

为了更加方便的实时调试公式与公式对应的图表，一位极其熟悉LaTeX，也熟悉Markdown的国人yihui同学，意识到LaTeX它可以作为最终格式生成。在他的大作——R包中的knitr，提供了Markdown支持。并说服R社区主流编辑器厂家，开源软件RStudio 提供 Markdown支持，从而使得Rmd这种新格式开始流行。我们有幸看到这个重要格式的诞生，国人的贡献如此重要。

在Mac上安装R语言和RStudio如下所示。

### 1. install r language

>brew tap homebrew/science
brew install r

### 2. download rstudio and install

download latest version from the url below:

>https://www.rstudio.com/products/rstudio/download/

Rstudio等的配置等叙述可以参考： [Markdown写作浅谈](http://www.yangzhiping.com/tech/r-markdown-knitr.html)

## 参考

[1]. [Markdown——入门指南](http://www.jianshu.com/p/1e402922ee32/)

[2]. [Markdown中文版语法说明](http://wowubuntu.com/markdown/basic.html)

[3]. [创始人 John Gruber 的 Markdown 语法说明](http://daringfireball.net/projects/markdown/syntax)

[4]. [使用Atom打造无懈可击的Markdown编辑器](http://www.cnblogs.com/fanzhidongyzby/p/6637084.html)

[5]. [Markdown写作浅谈](http://www.yangzhiping.com/tech/r-markdown-knitr.html)
