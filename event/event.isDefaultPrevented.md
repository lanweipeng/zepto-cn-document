event.isDefaultPrevented()  ⇒ boolean
如果为此事件实例调用了 proventDefault () ，则返回 true。这可以作为本机默认防止属性(在某些浏览器中缺少或不可靠)的跨平台替代方案
```js
// 触发自定义事件并检查该事件是否被取消
var event = $.Event('custom')
element.trigger(event)
event.isDefaultPrevented()
```