bind(type, function(e){ ... })  ⇒ self
bind(type, [data], function(e){ ... })  ⇒ self v1.1+
bind({ type: handler, type2: handler2, ... })  ⇒ self
bind({ type: handler, type2: handler2, ... }, [data])  ⇒ self v1.1+
将事件处理程序附加到元素。