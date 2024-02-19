text()  ⇒ string
text(content)  ⇒ self
text(function(index, oldText){ ... })  ⇒ self v1.1.4+
获取或设置集合中元素的文本内容。当没有给出内容时，返回集合中所有元素的文本内容，如果不存在元素，则返回 null。给定内容时，使用它替换集合中每个元素的文本内容。这类似于 HTML，但是它不能用于获取或设置 HTML