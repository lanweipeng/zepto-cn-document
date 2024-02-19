insertAfter(target)  ⇒ self
在 DOM 中的目标元素之后插入当前集合中的元素。这类似于 after，但操作是相反的。
```js
$('<p>Emphasis mine.</p>').insertAfter('blockquote')
```