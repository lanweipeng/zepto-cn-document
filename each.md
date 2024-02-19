each(function(index, item){ ... })  ⇒ self
迭代集合中的每个元素。在迭代器函数中，这个关键字引用当前项(也作为第二个参数传递给函数)。如果迭代器函数返回 false，则迭代停止。
```js
$('form input').each(function(index){
  console.log('input %d is: %o', index, this)
})
```