DOM库
包含操作DOM的常用方法以及兼容性处理

/*base.js*/

isNum、isStr、isBoo...检测数据类型的方法

each:实现数组和对象的遍历

listToArray:实现将类数组转换为数组

extend:在DOM库上扩展方法

----

/*style.js*/

css:设置或者获取元素的style样式值

setGroupCss:批量设置元素的样式属性值

offset:获取当前元素距离body的偏移量(上偏移top 和 左偏移left)

win:设置或者获取浏览器的盒子模型信息

hasClass:判断当前元素是否拥有某一个样式类名

addClass:给当前元素增加样式类名

removeClass:移除当前元素的样式类名

toggleClass:如果当前样式类名存在,则是移除,不存在则是增加



----

/*query.js*/

getElementsByClass:通过元素的样式类名获取一个元素集合

children:获取当前元素下所有指定标签名的元素子节点集合

prev:获取当前元素的上一个哥哥元素节点

prevAll:获取当前元素的所有的哥哥元素节点

getIndex:获取当前元素的索引

next:获取当前元素的下一个弟弟元素节点

nextAll:获取当前元素的所有的弟弟元素节点

sibling:获取当前元素的相邻两个兄弟元素节点(哥哥+弟弟)

siblings:获取当前元素的所有的兄弟元素节点

first:获取当前元素指定标签名的所有元素子节点中的第一个

last:获取当前元素指定标签名字的所有元素子节点中的最后一个


---
/*operation.js*/


attr:获取或者设置当前元素的自定义属性

html:获取或者设置当前元素的内容

val:获取或者设置当前表单元素的value值

prepend:向指定容器的开头增加元素(依赖query.js)

insertAfter:向指定容器中某个元素之前增加新元素(依赖query.js)