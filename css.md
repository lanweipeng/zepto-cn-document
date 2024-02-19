css(property)  ⇒ value
css([property1, property2, ...])  ⇒ object v1.1+
css(property, value)  ⇒ self
css({ property: value, property2: value2, ... })  ⇒ self
读取或设置 DOM 元素的 CSS 属性。如果没有给定值，则返回集合中第一个元素的 CSS 属性。当给定一个值时，将集合中每个元素的属性设置为该值。

通过传递一个属性名数组，可以同时检索多个属性。可以通过向方法传递对象来设置多个属性。

当属性的值为空(''、null或undefined)时，将删除该属性。当给定一个无单位数值时，对于需要单位的属性，“ px”会被附加到它后面。
```css
var elem = $('h1')
elem.css('background-color')          // 读值
elem.css('background-color', '#369')  // 写值
elem.css('background-color', '')      // 删值

// 设置多个属性
elem.css({ backgroundColor: '#8EE', fontSize: 28 })

// 读取多个属性值
elem.css(['backgroundColor', 'fontSize'])['fontSize']
```