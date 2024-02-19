# zepto 中文文档

[官方文档](https://zeptojs.com/)
[中文文档](http://www.wenshuai.cn/Manual/Zepto/#live)

Zepto 是一个面向现代浏览器的极简 JavaScript 库，其 API 基本上与 jQuery 兼容。如果你用过 jQuery，那你肯定也知道如何使用 Zepto。

虽然100% 的 jQuery 覆盖率不是一个设计目标，但是提供的 API 与 jQuery 相匹配。我们的目标是拥有一个大约5-10k 的模块化库，它可以快速下载和执行，拥有一个熟悉的、通用的 API，因此您可以集中精力完成工作。

## 浏览器支持
### 主要部分（100%支持）
- Safari 6+ (Mac)
- Chrome 30+ (Windows, Mac, Android, iOS, Linux, Chrome OS)
- Firefox 24+ (Windows, Mac, Android, Linux, Firefox OS)
- iOS 5+ Safari
- Android 2.3+ Browser
- Internet Explorer 10+ (Windows, Windows Phone)
### 次要目标(完全支持或大部分支持)
- iOS 3+ Safari
- Chrome <30
- Firefox 4+
- Safari <6
- Android Browser 2.2
- Opera 10+
- webOS 1.4.5+ Browser
- BlackBerry Tablet OS 1.0.7+ Browser
- Amazon Silk 1.0+
- Other WebKit-based browsers/runtimes

请注意，Zepto 的一些可选特性专门针对移动浏览器; 因为最初的项目目标是专门为移动 web 提供一个更精简的 jQuery 替代品。

Zepto 是浏览器扩展(Safari、 Chrome 和 Firefox)以及在本地应用框架(如 PhoneGap)中开发基于 HTML 的视图的不错选择。

简而言之，Zepto 可以在任何现代浏览器和类似浏览器的环境中工作。Zepto 不支持旧的 Internet Explorer 版本(< 10)。

## 主要方法
- [$()](./$().md)
- [$.camelCase](./$.camelCase.md)
- [$.contains](./$.contains.md)
- [$.each](./$.each.md)
- [$.extend](./$.extend.md)
- [$.fn](./$.fn.md)
- [$.grep](./$.grep.md)
- [$.isArray](./$.isArray.md)
- [$.inArray](./$.inArray.md)
- [$.isFunction](./$.isFunction.md)
- [$.isNumeric](./$.isNumeric.md)
- [$.isPlainObject](./$.isPlainObject.md)
- [$.isWindow](./$.isWindow.md)
- [$.map](./$.map.md)
- [$.noop](./$.noop.md)
- [$.parseJSON](./$.parseJSON.md)
- [$.trim](./$.trim.md)
- [$.type](./$.type.md)
- [add](./add.md)
- [addClass](./addClass.md)
- [after](./after.md)
- [append](./append.md)
- [appendTo](./appendTo.md)
- [attr](./attr.md)
- [before](./before.md)
- [children](./children.md)
- [clone](./clone.md)
- [closest](./closest.md)
- [concat](./concat.md)
- [conten](./conten)
- [contents](./contents.md)
- [css](css.md)
- [data](data.md)
- [each](each.md)
- [empty](empty.md)
- [eq](eq.md)
- [filter](filter.md)
- [find](find.md)
- [first](first.md)
- [forEach](forEach.md)
- [get](get.md)
- [has](has.md)
- [hasClass](hasClass.md)
- [height](height.md)
- [hide](hide.md)
- [html](html.md)
- [index](index.md)
- [indexOf](indexOf.md)
- [insertAfter](insertAfter.md)
- [insertBefore](insertBefore.md)
- [is](is.md)
- [last](last.md)
- [map](map.md)
- [next](next.md)
- [not](not.md)
- [offset](offset.md)
- [offsetParent](offsetParent.md)
- [parent](parent.md)
- [pluck](pluck.md)
- [position](position.md)
- [prepend](prepend.md)
- [prependTo](prependTo.md)
- [prev](prev.md)
- [prop](prop.md)
- [push](push.md)
- [ready](ready.md)
- [reduce](reduce.md)
- [remove](remove.md)
- [removeAttr](removeAttr.md)
- [removeClass](removeClass.md)
- [removeProp](removeProp.md)
- [replaceWith](replaceWith.md)
- [scrollLeft](scrollLeft.md)
- [scrollTop](scrollTop.md)
- [show](show.md)
- [siblings](siblings.md)
- [size](size.md)
- [slice](slice.md)
- [text](text.md)
- [toggle](toggle.md)
- [toggleClass](toggleClass.md)
- [unwrap](unwrap.md)
- [val](val.md)
- [width](width.md)
- [wrap](wrap.md)
- [wrapAll](wrapAll.md)
- [wrapInner](wrapInner.md)

## 检查方法
“检测”模块有助于根据不同的环境对网站或应用程序进行微调，并帮助您区分手机和平板电脑，以及不同的浏览器引擎和操作系统版本。
```js
//如果应用以下布尔标志，则将其设置为 true,

//如果没有，它们要么被设置为“ false”，要么被设置为“未定义”。

//我们建议在访问它们时使用“ ! !”前缀以强制使用布尔值。

// general device type
$.os.phone
$.os.tablet

// specific OS
$.os.ios
$.os.android
$.os.webos
$.os.blackberry
$.os.bb10
$.os.rimtabletos

// specific device type
$.os.iphone
$.os.ipad
$.os.ipod // [v1.1]
$.os.touchpad
$.os.kindle

// specific browser
$.browser.chrome
$.browser.firefox
$.browser.safari // [v1.1]
$.browser.webview // (iOS) [v1.1]
$.browser.silk
$.browser.playbook
$.browser.ie // [v1.1]

//另外，版本信息也是可用的。

//下面是运行 iOS 6.1的 iPhone 的返回值。
!!$.os.phone         // => true
!!$.os.iphone        // => true
!!$.os.ios           // => true
$.os.version       // => "6.1"
$.browser.version  // => "536.26"

```
- []()
- []()
- []()
- []()
- []()
- []()
- []()
- []()