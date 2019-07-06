# the book of shaders

电子版书籍代码备份

[电子版原址](https://thebookofshaders.com/?lan=ch)

作者还附加了一个在线实时编辑查看的工具，另附[链接](https://thebookofshaders.com/)

---



## 颜色

在讲到颜色混合**mix**时，作者实现了一部分的缓动实现，可参考[easing.frag](./easing.frag)

同样是颜色混合还有一个例子值得研究，它可视化了两种颜色的混合比例，线段代表比例。

[代码链接](./mix_line.frag)



效果如图



![mix_line](./png/mix_line.png)

接下来，介绍用色彩空间来讨论颜色，HSB代表色相，饱和度和亮度，代表着极坐标系下的表示方法。作者也给出了HSB和RGB两种不同表示下的转换，[translation_color.frag](./translation_color.frag)

效果如下：

![HSB_test](./png/HSB_test.png)



还有一个选择色轮的绘制也是挺有意思的，代码[color_select.frag](./color_select.frag)

效果如图

![HSB_color](./png/HSB_circle.png)