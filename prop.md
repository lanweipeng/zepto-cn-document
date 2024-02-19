prop(name)  ⇒ value
prop(name, value)  ⇒ self
prop(name, function(index, oldValue){ ... })  ⇒ self
prop({ name: value, name2: value2, ... })  ⇒ self
读取或设置 DOM 元素的属性。如果读取的属性值随着用户交互的时间而变化(如checked和selected) ，则这应优先于 attr。

诸如 for、 class、 readOnly 和类似的短小写名称将映射到实际的属性，例如 htmlFor、 className、 readOnly 等。