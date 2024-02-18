attr(name)  ⇒ string
attr(name, value)  ⇒ self
attr(name, function(index, oldValue){ ... })  ⇒ self
attr({ name: value, name2: value2, ... })  ⇒ self
读取或设置 DOM 属性。如果没有给定值，则从集合中的第一个元素中读取指定的属性。给定值时，将集合中每个元素的属性设置为该值。当 value 为 null 时，将删除该属性(如 RemoveAttr)。可以通过传递具有名称-值对的对象来设置多个属性。

若要读取选中或选中的 DOM 属性，请使用 prop。
```js
var form = $('form')
form.attr('action')             //=> 读值
form.attr('action', '/create')  //=> 写值
form.attr('action', null)       //=> 删值

// 多个属性
form.attr({
  action: '/create',
  method: 'post'
})
```