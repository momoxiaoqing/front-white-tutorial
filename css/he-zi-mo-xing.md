### 盒子 模型

在一个文档中，每个元素都被表示为一个矩形的盒子。

每个盒子有四个边：外边距边, 边框边, 内填充边 与 内容边。

如图：

![](/assets/boxmodel.png)

1、W3C标准盒子模型 VS  IE标准盒子模型

盒子模型主要分为：W3C标准 和 IE标准盒子模型。大多数浏览器采用W3C标准模型，而IE中则采用Microsoft自己的标准。

W3C标准盒子模型：元素宽度=content.width+padding+border    高度类似

IE标准盒子模型：元素宽度=content.width （content.width包含padding+border）

2、块元素的margin上下会兼并

![](/assets/小练习 .png)

