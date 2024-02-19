html()  ⇒ string
html(content)  ⇒ self
html(function(index, oldHtml){ ... })  ⇒ self
获取或设置集合中元素的 HTML 内容。当没有给定内容时，返回第一个元素的 innerHTML。当给定内容时，使用它替换每个元素的内容。内容可以是append中描述的任何类型。
```js
// autolink everything that looks like a Twitter username
$('.comment p').html(function(idx, oldHtml){
  return oldHtml.replace(/(^|\W)@(\w{1,15})/g,
    '$1@<a href="http://twitter.com/$2">$2</a>')
})
```