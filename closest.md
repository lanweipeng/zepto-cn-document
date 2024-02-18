closest(selector, [context])  ⇒ collection
closest(collection)  ⇒ collection v1.0+
closest(element)  ⇒ collection v1.0+
从当前元素向上遍历，找到与选择器匹配的第一个元素。如果给定了上下文节点，则仅考虑作为其后代的元素。此方法类似于父级(选择器) ，但它只返回匹配的第一个祖先。

如果给定了 Zepto 集合或元素，则生成的元素必须匹配给定的元素之一，而不是选择器。
```js
var input = $('input[type=text]')
input.closest('form')
```