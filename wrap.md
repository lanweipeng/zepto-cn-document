wrap(structure)  ⇒ self
wrap(function(index){ ... })  ⇒ self v1.0+
将集合的每个元素分别包装在 DOM 结构中。结构可以是单个元素或多个嵌套元素，可以作为 HTML 字符串或 DOM 节点传递，也可以作为为每个元素调用并返回前两种类型之一的函数传递。

请记住，在操作作为 DOM 一部分的节点时，封装效果最好。当对一个新元素调用 wrash ()并将结果插入到文档中时，该元素将失去包装。
```js
// wrap each button in a separate span:
$('.buttons a').wrap('<span>')

// wrap each code block in a div and pre:
$('code').wrap('<div class=highlight><pre /></div>')

// wrap all form inputs in a span with classname
// corresponding to input type:
$('input').wrap(function(index){
  return '<span class=' + this.type + 'field />'
})
//=> <span class=textfield><input type=text /></span>,
//   <span class=searchfield><input type=search /></span>

// WARNING: will not work as expected!
$('<em>broken</em>').wrap('<li>').appendTo(document.body)
// do this instead:
$('<em>better</em>').appendTo(document.body).wrap('<li>')
```