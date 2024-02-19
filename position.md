position()  ⇒ object

获取集合中第一个元素的positoin,跟 `offsetParent` 类似。当将一个元素绝对定位为与另一个元素对齐时，此信息非常有用。

返回一个具有属性的对象: top, left.
```js
var pos = element.position()

// position a tooltip relative to the element
$('#tooltip').css({
  position: 'absolute',
  top: pos.top - 30,
  left: pos.left
})
```