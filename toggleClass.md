toggleClass(names, [setting])  ⇒ self
toggleClass(function(index, oldClassNames){ ... }, [setting])  ⇒ self
在集合中的每个元素中切换给定的类名(以空格分隔)。如果类名出现在元素上，则删除该类名; 否则添加该类名。如果设置存在，则此方法的行为类似于 addClass (如果设置为 true) ，否则为 RemoveClass。