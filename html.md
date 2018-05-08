### 一、各种标签

1、根元素：&lt;html&gt;  一个HTML文档的根（顶级元素）

2、元数据：含有页面的相关信息，包括样式、脚本及数据，能帮助一些软件 \(如搜索引擎， 浏览器等等）更好地运用和渲染页面。对于样式和脚本的元数据，可以直接在网页里定义，也可以链接到包含相关信息的外部文件。

| [`<link>`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/link) | **HTML**中`<link>`元素指定了外部资源与当前文档的关系。 这个元素的用途包括为导航定义一个关系框架。这个元素经常用来链接样式表（如CSS文件）。 |
| :--- | :--- |
| [`<meta>`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/meta) | HTML`<meta>`元素表示那些不能由其它HTML元相关元素 \( [`<base>`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/base),[`<link>`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/link),[`<script>`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/script),[`<style>`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/style)或[`<title>`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/title)\) 之一表示的任何元数据信息. |
| [`<style>`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/style) | HTML的**&lt;style&gt;**元素包含了文档的样式化信息或者文档的一部分，该标签的样式信息通常是[CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)的格式。 |
| [`<title>`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/title) | **HTML**`<title>`**元素**定义文档的标题，显示在浏览器的标题栏或标签页上。它只可以包含文本，若是包含有标签，则包含的任何标签都不会被解释。 |

3、脚本：为了创建动态内容和 Web 应用程序，HTML 支持使用脚本语言，最突出的就是 JavaScript。某些元素支持此功能。

| 元素 | 描述 |
| :--- | :--- |
| [`<canvas>`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/canvas) | **&lt;canvas&gt;元素**可被用来通过脚本（通常是JavaScript）绘制图形。比如,它可以被用来绘制图形,制作图片集合,甚至用来实现动画效果。你可以\(也应该\)在元素标签内写入可提供替代的的代码内容，这些内容将会在在旧的、不支持&lt;canvas&gt;元素的浏览器或是禁用了JavaScript的浏览器内渲染并展现。 |
| [`<noscript>`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/noscript) | 如果页面上的脚本类型不受支持或者当前在浏览器中关闭了脚本，则在HTML &lt;noscript&gt; 元素中定义脚本未被执行时的替代内容。&lt;/noscript&gt; |
| [`<script>`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/script) | **HTML**`<script>`** 元素**用于嵌入或引用可执行脚本。 |

4、其他

重点掌握以下元素就可以：

* &lt;div&gt;

* &lt;h1&gt;.....&lt;h6&gt;

* &lt;p&gt;

* &lt;ul&gt; &lt;li&gt;

* &lt;a&gt; &lt;span&gt; &lt;img&gt; &lt;br&gt; &lt;i&gt;

* &lt;form&gt; &lt;label&gt; &lt;input&gt; &lt;radio&gt; &lt;button&gt; &lt;select&gt; &lt;textarea&gt;  &lt;option&gt;

* &lt;table&gt; &lt;tbody&gt; &lt;tr&gt; &lt;td&gt;

了解以下：

* &lt;video&gt; ：视频
* &lt;audio&gt;：音频
* &lt;map&gt; +&lt;area&gt;：HTML &lt;map&gt; 属性 与 &lt;area&gt; 属性一起使用来定义一个图像映射\(一个可点击的链接区域\).

### 二、块元素&行内元素

块元素：占据其父元素（容器）的整个空间，因此创建了一个“块”，即占整行，如&lt;div&gt; &lt;h1&gt;-&lt;h6&gt; &lt;p&gt; &lt;ul&gt; &lt;li&gt;等；

行内元素：一个行内元素只占据它对应标签的边框所包含的空间，即不占整行，如&lt;span&gt; &lt;a&gt; &lt;input&gt;等；

注意：

1、可以相互转化，改变display属性即可

2、行内元素设置width无效，若要设置，需要将display改为inline-block

3、display常用值：

* block         象块类型元素一样显示。
* none          缺省值。象行内元素类型一样显示。
* inline-block  象行内元素一样显示，但其内容象块类型元素一样显示。
* list-item     象块类型元素一样显示，并添加样式列表标记。
* table         此元素会作为块级表格来显示
* inherit       规定应该从父元素继承 display 属性的值



