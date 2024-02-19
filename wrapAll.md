wrapAll(structure)  ⇒ self
将所有元素包装在一个单独的结构中。结构可以是单个元素或多个嵌套元素，可以作为 HTML 字符串或 DOM 节点传递。
```js
// wrap all buttons in a single div:
$('a.button').wrapAll('<div id=buttons />')
```