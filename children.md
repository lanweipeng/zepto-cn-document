
children([selector])  ⇒ collection
获取当前集合中每个元素的直接子元素。如果给定了选择器，则筛选结果以仅包含与 CSS 选择器匹配的结果。
```js
$('ol').children('*:nth-child(2n)')
//=> 列表的偶数item

```