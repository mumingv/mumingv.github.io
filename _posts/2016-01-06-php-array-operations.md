---
layout: post
title: PHP数组操作
category: PHP
tags: [PHP]
description: None
---

> 本文是对数组操作方法的一些总结，包括：创建、增加、删除、修改、遍历/查找等等。

PHP的数组可以简单理解为key/value（键值对）的组合，根据是否显式指定key，数组可以分为索引数组和关联数组。其实PHP内部是不区分是索引数组还是关联数组的，因为key可以是整数也可以是字符串（但不能是其他类型哦！），不仅如此，在一个数组中key的类型可以混用，即一部分value使用整数作为key，另一部分value使用字符串作为key。对于value，可以是任何类型。

简单来讲，对于一个value，如果没有给其显式指定key，则默认使用整数作为其key。


# 一、创建


### 空数组

**空数组**

<font size='5'>空数组</font>
<font size='4'>空数组</font>
<font size='3'>空数组</font>

让我们从创建一个空数组开始，

    $colors = array();

或者

    $colors = [];

# 二、
