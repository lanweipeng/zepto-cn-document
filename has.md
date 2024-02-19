has(selector)  ⇒ collection
has(node)  ⇒ collection
筛选当前集合，使其只包含具有任意数量的与选择器匹配的后代元素或包含特定 DOM 节点的元素。
```js
$('ol > li').has('a[href]')
//=>get only LI elements that contain links
```