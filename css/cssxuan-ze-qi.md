### 一、css选择器：

1、基础：

* 通配选择器：\*
* ID选择器：\#id
* 类选择器：.class
* 元素选择器：div
* 属性选择器：input\[type='radio'\]
* 子选择器：div&gt;p
* 后代选择器：div p

2、进阶：伪类选择器：

* :before  :after
* :nth-of-type\(n\)   :nth-last-of-type\(n\)
* :active :link :focus :visited :hover

3、优先级

| 优先级 | 选择器 | 权值 |
| :--- | :--- | :--- |
| 高 | !important | 1-0-0-0-0 |
|  | 内联 | 1-0-0-0 |
|  | ID选择器 | 1-0-0 |
|  | 类选择器、属性选择器、伪类选择器 | 1-0 |
| 低 | 标签选择器、伪对象选择器 | 1 |

大鱼吃小鱼，小鱼吃小虾，小虾吃泥巴：

![](/assets/specifishity1-1.png)

权值一样时，后面的样式覆盖前面的。

4、注意：&lt;a&gt;添加伪元素时，应遵循爱恨原则\(LVHA\)

* a:hover必须在a:link 和a:visited之后
* a:active必须在a:hover之后



