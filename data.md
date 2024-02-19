data(name)  ⇒ value
data(name, value)  ⇒ self
读取或写入 data-* DOM 属性。行为类似 attr，但是将 data-添加到属性名称之前。

在读取属性值时，应用以下转换: v1.0 +

将“ true”、“ false”和“ null”转换为相应的类型;

数值转换为实际的数值类型;

如果 JSON 是有效的，则解析 JSON 值;

其他所有内容都以字符串形式返回。

Zepto 的基本实现“ data ()”只存储字符串。要存储任意对象，可以在自定义构建的 Zepto 中包含可选的“数据”模块