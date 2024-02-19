not(selector)  ⇒ collection
not(collection)  ⇒ collection
not(function(index){ ... })  ⇒ collection
筛选当前集合以获取与 CSS 选择器不匹配的元素的新集合。如果给定的是另一个集合而不是选择器，则只返回其中不存在的元素。如果给定了一个函数，则只返回函数返回假值的元素。在函数内部，this 关键字引用当前元素。

相反，请参阅`filter`。