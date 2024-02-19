get()  ⇒ array
get(index)  ⇒ DOM node
从当前集合中获取所有元素或单个元素。如果没有给出索引，则返回普通数组中的所有元素。指定 index 时，只返回该位置的元素。这与 eq 的不同之处在于，返回的节点没有包装在 Zepto 集合中。
```js
$('div').eq(0)//Z{0:div}
$('div').get(0)//<div></div>
```
