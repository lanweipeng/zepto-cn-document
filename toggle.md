toggle([setting])  ⇒ self
根据第一个元素是否可见，在显示和隐藏每个元素之间切换。如果存在设置，则此方法的行为类似于 show  或 hide 
```js
var input = $('input[type=text]')
$('#too_long').toggle(input.val().length > 140)

```