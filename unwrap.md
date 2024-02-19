unwrap()  ⇒ self
删除集合中每个元素的直接父节点，并将其子节点放在各自的位置。基本上，这个方法在保留 DOM 中的当前元素的同时，删除了一个祖先级别。
```js
$(document.body).append('<div id=wrapper><p>Content</p></div>')
$('#wrapper p').unwrap().parents()  //=> [<body>, <html>]
```