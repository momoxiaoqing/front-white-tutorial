### 一、长度单位

| 单位 | 意义 | 优缺点 |
| :--- | :--- | :--- |
| px | 像素 |  |
| em | 以当前元素字体的大小为单位 |  |
| rem | 相对于根元素的字体大小的单位 | 适用于移动端 |
| % | 相对于父元素百分比 |  |
| vh | 相对于当前视窗高度 | 兼容性不好，IE9以上 |
| vw | 相对于当前视窗宽度 | 同上 |

### 二、居中

1、块元素：

* 水平居中：

  ```
    width：100px; //设置宽度

    margin: auto;
  ```

* 垂直居中：设置marign

2、行内元素

* 水平居中：父元素：text-align:center;

* 垂直居中：设置padding或者line-height

### 三、媒体查询

根据当前设备的屏幕大小决定是否显示某些样式（本人自话，不一定科学准确）

&lt;!-- link元素中的CSS媒体查询 --&gt;

&lt;link rel="stylesheet" media="\(max-width: 800px\)" href="example.css" /&gt;



&lt;!-- 样式表中的CSS媒体查询 --&gt;

&lt;style&gt;

@media \(max-width: 600px\) {

  .facet\_sidebar {

    display: none;

  }

}

&lt;/style&gt;

