---
title: Node的流程管理
author: imkven
date: 2015-04-22
template: article.jade
---

刚接触Node的时候，如果参考官网，我们会编程出很难管理的回调地狱。我第一份Node项目里有个函数，拥有至少20层的回调地狱。代码很难阅读和出错时也很难捉虫。之后，我选择了`async`做为我日后Node流程管理的插件。

`aync`在使用顺手，而且文档简单易明，