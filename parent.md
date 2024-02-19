parent([selector])  ⇒ collection
获取集合中每个元素的直接父元素。如果给定 CSS 选择器，则筛选结果只包含与选择器匹配的结果。
若要只获取直接父级，请使用  `parent`。若要只获取与选择器匹配的第一个祖级，请使用`closest`。
```js
$('h1').parents()   //=> [<div#container>, <body>, <html>]

```