---
layout: post
title: tablesort 前端表格排序
categories: [blog ]
tags: [Js, ]
description: fork自tristen/tablesort的一个轻量级无依赖的前端表格排序程序
---


## tablesort是一个轻量级无依赖的前端表格排序程序

本文在tristen/tablesort的基础上增加列静态data-sort-static="true"属性，保持列不加入排序。

增加这一属性的目的是本人在前端表格中往往第一列都是行序号，而之前版本中点击排序之后行序号也跟着变化了，因此想增加一个功能保持序号列不变化，于是增加了data-sort-static属性。

详细文档请参见[http://zengkv.com/tablesort/demo/](http://zengkv.com/tablesort/demo/)

git地址[https://github.com/zengkv/tablesort](https://github.com/zengkv/tablesort)
