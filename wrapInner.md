wrapInner(structure)  ⇒ self
wrapInner(function(index){ ... })  ⇒ self v1.0+
将每个元素的内容分别包装在一个结构中。结构可以是单个元素或多个嵌套元素，可以作为 HTML 字符串或 DOM 节点传递，也可以作为为每个元素调用并返回前两种类型之一的函数传递。
```js
// wrap the contents of each navigation link in a span:
$('nav a').wrapInner('<span>')

// wrap the contents of each list item in a paragraph and emphasis:
$('ol li').wrapInner('<p><em /></p>')
```