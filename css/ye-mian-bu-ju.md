### 一、前端布局方案主要有三种：

* 传统布局方案（借助浮动、table、定位等手段）：兼容性好，能兼容到IE6；但是有高度塌陷、不灵活

* flex布局方案：灵活，垂直居中很方便；但兼容性不好，IE9以上

* grid布局方案：和flex差不多，但兼容性比flex差的多，IE不支持

### 二、浮动float

float会引起父元素高度塌陷

解决方法有很多种，本人一般用给父元素添加：

```
  overflow: auto;
  zoom: 1;
```

### 三、定位

position取值：

* static

默认，正常流， top, right, bottom, left 和 z-index 属性无效。

* relative

相对于正常流位置，对 table-\*-group, table-row, table-column, table-cell, table-caption 元素无效。

* absolute

不为元素预留空间，相对于最近的非 static 定位祖先元素的偏移，来确定元素位置。

可以设置外边距（margins），且不会与其他边距合并。

* fixed

不为元素预留空间，相对于窗口的位置来指定元素位置。

元素的位置在屏幕滚动时不会改变。

fixed 属性会创建新的层叠上下文。当元素祖先的 transform  属性非 none 时，容器由视口改为该祖先。

* sticky 

粘性定位盒位置根据正常流计算\(这称为正常流动中的位置\)，然后相对于该元素在流中的 flow root（BFC）和 containing block（最近的块级祖先元素）定位。在所有情况下（即便被定位元素为 table 时），该元素定位均不对后续元素造成影响。当元素 B 被粘性定位时，后续元素的位置仍按照 B 未定位时的位置来确定。

position: sticky 对 table 元素的效果与 position: relative 相同。

详细可查看：[MDN](https://developer.mozilla.org/zh-CN/docs/Web/CSS/position)

