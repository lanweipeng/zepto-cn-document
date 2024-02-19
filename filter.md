filter(selector)  ⇒ collection
filter(function(index){ ... })  ⇒ collection v1.0+
筛选集合以仅包含与 CSS 选择器匹配的项。如果给定了一个函数，只返回函数返回真值的元素。在函数内部，this 关键字引用当前元素。

相反，请看[not](not.md)。