insertBefore(target)  ⇒ self
在 DOM 中的每个目标元素之前插入当前集合中的元素。这和`before`一样，但操作是相反的。
```js
$('<p>See the following table:</p>').insertBefore('table')
```