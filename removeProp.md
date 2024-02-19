removeProp(name)  ⇒ self
从集合中的每个 DOM 节点中删除一个属性。这是通过 JavaScript 的 delete 操作符完成的。请注意，尝试删除一些内置的 DOM 属性(如 className 或 maxLlength)不会产生任何影响，因为浏览器不允许删除这些属性。