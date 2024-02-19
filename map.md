map(function(index, item){ ... })  ⇒ collection
遍历所有元素并收集迭代器函数的返回值。在迭代器函数中，这个关键字引用当前项(也作为第二个参数传递给函数)。

返回迭代器函数的结果集合，过滤掉`null`和`undefined`。