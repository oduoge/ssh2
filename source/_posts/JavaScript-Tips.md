---
title: JavaScript 使用的小 Tips
date: 2019-07-22 14:48:16
tags:
- tips
categories:
- 前端
- JavaScript
---

记录在使用`JavaScript` 过程中遇到的一些小 `Tips`

<!----more ---->

## 数组赋值引用

```js
let arrA = [0, 1, 2];
let arrB = arrA;
```
对<code>arrB</code>的操作也会影响到<code>arrA</code>。如果想避免这种情况，可以使用<code>concat()</code>方法：
```js
let arrA = [0, 1, 2];
let arrB = arrA.concat();
```
对象数组，可采用循环遍历的方式创建新的数组

