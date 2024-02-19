pluck(property)  ⇒ array
从集合中每个元素的命名属性中获取值，并过滤掉null和undefined。

```js
$('body > *').pluck('nodeName') // => ["DIV", "SCRIPT"]

// implementation of Zepto's `next` method
$.fn.next = function(){ 
  return $(this.pluck('nextElementSibling')) 
}
```
这是 Zepto 提供的方法，它不是 jQueryAPI 的一部分。