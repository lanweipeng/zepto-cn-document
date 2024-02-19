val()  ⇒ string
val(value)  ⇒ self
val(function(index, oldValue){ ... })  ⇒ self
获取或设置form控件的值。当没有给出值时，返回第一个元素的值。对于 < select multi > ，返回一个值数组。当给定一个值时，将所有元素设置为该值。