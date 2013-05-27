---
layout: post
title: Jekyll不好部署？你完全可以绕过去！
categories: [instruction]
tags: [介绍, Jekyll]

---
羡慕这么多博客家们漂亮的Jekyll下的Github博客，一时心痒手痒，想照葫芦画一个。结果是一个字：难！但最终还是靠着github for windows成功clone造了一个。其中经验其实很简单，这世界特别是IT世界变化快，别盲从过来人的经验，他们的经验往往已经过时，老老实实看wiki或help文档比什么经验都管用。
####丢掉Ruby，丢掉Jekyll，丢掉Octopress，丢掉Cygwin……，只需记住你要什么
不就是想要一个github博客吗，犯得着从linux学起整一大堆不好弄弄好就不管用的玩意儿吗？本想偷懒，随手就google了Jekyll+Github，苦难开始了。linux虽然不是完全生疏，但你想要装好Ruby来安装Jekyll还真是费工夫。其中乱七八糟的包依赖关系、版本号就得耗尽你的耐心。不想在linux系统上整，人家建议你用Cygwin模拟着弄。安装好了的，都说三分钟搞掂，你真要按他的方法，三天不见得能通。
####fork+github for windows，你真的有希望三分钟内搞掂
当然理解到这一步，三分钟不够。到了这一步，也真理解了[git](http://github.com/)为何在开源领域要胜过[sf](http://sourceforge.net/)了。
- 知道一下Github是怎么玩的还是有必要的，[Roger Dudler](http://rogerdudler.github.io/git-guide/index.zh.html)的脑图是简介挺管用的，加上[GFW的官方help](http://windows.github.com/help.html/)不会有任何问题。
- 挑选一个喜欢的直接fork修改。别难为情，这是科学知识和技术积累的一般模式。自己再发明一遍轮子没必要。[谢益辉](http://yihui.name)这小伙子统计思想值得称道而且coding至简实用美观，他的[统计之都](http://cos.name/)是统计学习必看的，直接fork了。
- 当然要想保留评论功能得去自己注册[disquz comment](http://disqus.com/)加入到代码里边。

这阵子研究OSS，这个博客的搭建虽是浅尝，但也算是有了点感性认识吧。
