---
title: 前端学习笔记
---
加油啊，学前端的大哥哥！

## 用 appearance 属性清除默认样式
```CSS
-webkit-appearance:none;
-moz-appearance: none;
-ms-appearance:none;
-o-appearance:none;
appearance:none;
```
可以用来清除 input，button，select 等默认样式。

## 清除浏览器默认样式
使用vscode 中的css reset 插件，快捷输入：cssr。

## sans-serif
定义font-family 时，在最后加一个sans-serif 这样即使列出的字体都不能用， 默认的sans-serif 字体能保证调用。

## window.onload()
用来在网页加载完成后执行操作
