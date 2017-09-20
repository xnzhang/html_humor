# <center>html_humor--学习html各种姿势
* 此项目用于html css javascript..前端开发基础技能的学习记录,学习资料来源于
[w3school](http://www.w3school.com.cn/index.html)

> 1.HTML 基础标签实例:

1. body 元素中的内容才是被网页现实的。
2. title 元素的内容会显示在浏览器的标题栏中。
3. p元素包裹一个段落且多余的空行和换行会被忽略。
4. br元素代表一个换行。
5. h1....6,正真的开发中只标识一个标题,具体的大小样式还是会用css定义的。（因为一般开发都会将默认样式格式化）

> 2.HTML 文本格式化实例

* [格式化标签](http://www.w3school.com.cn/tiy/t.asp?f=html_textformatting)有：b,strong,big,em,i,small,sub,sup。\
[预格式化标签](http://www.w3school.com.cn/tiy/t.asp?f=html_preformattedtext)：pre--保留文本空格和换行。\
[计算机输出](http://www.w3school.com.cn/tiy/t.asp?f=html_computeroutput)标签: code,kbd,tt,samp,var。\
[地址](http://www.w3school.com.cn/tiy/t.asp?f=html_address)：href="mailto:webmaster@example.com"，标准的邮件格式。\
[缩写和首字母缩写](http://www.w3school.com.cn/tiy/t.asp?f=html_abbracronym)：abbr,acronym，鼠标停留显示说明。\
[文字方向](](http://www.w3school.com.cn/tiy/t.asp?f=html_bdo)):bdo dir="rtl"，文字从右往左输出。\
[块引用](http://www.w3school.com.cn/tiy/t.asp?f=html_quotations)： blockquote，q，为文字添加一个引用。\
[删除字效果和插入字效果](http://www.w3school.com.cn/tiy/t.asp?f=html_delins)：del，ins，为文字添加删除线和下划线。

> 3.HTML 链接实例

* [一个超级链接](http://www.w3school.com.cn/tiy/t.asp?f=html_links):a href="/index.html"。\
在新的浏览器窗口打开链接：target 属性设置为 "_blank"。 链接到同一个页面的不同位置：用name标记做跳转。跳出框架:target="_top"。 \
一个简单的[电子邮件链接](http://www.w3school.com.cn/tiy/t.asp?f=html_mailto)：a href="mailto:someone@microsoft.com?subject=Hello%20again"

> 4.HTML 框架实例
 
* 由于标签，[frameset](http://www.w3school.com.cn/html/html_frames.asp) 已过期，就不再做了解

> 5.HTML 表格实例

* 表格由 [table](http://www.w3school.com.cn/tiy/t.asp?f=html_tables) 标签开始，\
表格行由 tr 标签开始，表格数据由 td 标签开始，表格头由[th标签](http://www.w3school.com.cn/tiy/t.asp?f=html_table_headers)表示。\
边框用border="1"表示。不添加内容即为空的单元格。表格标题用[caption](http://www.w3school.com.cn/tiy/t.asp?f=html_tables3)标签表示。\
[colspan="2"](http://www.w3school.com.cn/tiy/t.asp?f=html_table_span)表示表格单元夸两列。[rowspan="2"](http://www.w3school.com.cn/tiy/t.asp?f=html_table_span)表示表格单元夸两行。\
单元格内也可以添加其他标签。[单元格边距](http://www.w3school.com.cn/tiy/t.asp?f=html_table_cellpadding)有cellpadding表示。\
[单元格间距](http://www.w3school.com.cn/tiy/t.asp?f=html_table_cellspacing)由cellspacing表示。\
[单元格内容位置](http://www.w3school.com.cn/tiy/t.asp?f=html_table_align)由align="left"表示。\
[frame="box"](http://www.w3school.com.cn/tiy/t.asp?f=html_table_frame)用来设置表格外边框，但是在IE中不一定能正确显示。

> 6.HTML 列表实例

* [ul标签](http://www.w3school.com.cn/tiy/t.asp?f=html_list_unordered)代表一个无序列表。\
[ol](http://www.w3school.com.cn/tiy/t.asp?f=html_list_ordered)代表一个有序列表。列表项由li表示。\
常用的[列表项类型](http://www.w3school.com.cn/tiy/t.asp?f=html_lists_unordered)有：ul type="square"，"circle"，"disc"。\
当然列表也内置了[许多类型](http://www.w3school.com.cn/tiy/t.asp?f=html_lists_ordered)。\
列表中同样也可以添加列表。如果需要使用列表项和注释的组合就可以使用[定义列表](http://www.w3school.com.cn/tiy/t.asp?f=html_list_definition)由标签dl表示，dt标签表示列表名，dd标签表示列表注释。

> 7.HTML 表单与输入实例

* 表单在前端开发中出现非常多，也很好使用。input标签用于显示常见的表单类型，type=“text”，“password”，“checkbox”，“radio”，“button”,\
分别表示文本[输入框](http://www.w3school.com.cn/tiy/t.asp?f=html_inputfields)，\
[密码输入框](http://www.w3school.com.cn/tiy/t.asp?f=html_passwordfields)，\
[复选框](http://www.w3school.com.cn/tiy/t.asp?f=html_checkboxes)，\
[单选框](http://www.w3school.com.cn/tiy/t.asp?f=html_radiobuttons)，\
[按钮](http://www.w3school.com.cn/tiy/t.asp?f=html_button)。\
下拉选项由[select](http://www.w3school.com.cn/tiy/t.asp?f=html_dropdownbox)标签包裹，option表示下拉项。\
[textarea cols="30" rows="5"](http://www.w3school.com.cn/tiy/s.asp?f=demo_html_textarea)表示一个30列5行的文本域，\
用于输入文本。form标签下还有一个[fieldset](http://www.w3school.com.cn/tiy/t.asp?f=html_fieldset)标签配合legend可以为表单添加一个带标题的边框。

> 8.表单实例

* form标签表示表单，可以是设置点击提交目标由[action标签](http://www.w3school.com.cn/tiy/t.asp?f=html_form_submit)表示，\
请求类型由[method](http://www.w3school.com.cn/tiy/t.asp?f=html_form_mail)标签表示。\
除了提交按钮[submit](http://www.w3school.com.cn/tiy/t.asp?f=html_form_checkbox)，\
还有重置按钮[reset](http://www.w3school.com.cn/tiy/t.asp?f=html_form_mail)。

> 9.HTML 图像实例

* img标签是内联标签（不换行）。所以一段p便签标记的文本中，[img标签](http://www.w3school.com.cn/tiy/t.asp?f=html_image)可以随意插入。\
以颜色作为背景使用bgcolor属性，以图片作为背景应该使用[background属性](http://www.w3school.com.cn/tiy/t.asp?f=html_backgroundimage)。\
当图片在文字中时，为了保证图片的显示位置可以使用align=“middle”，“top”，“bottom”，“left”，“right”\
[前三个值](http://www.w3school.com.cn/tiy/t.asp?f=html_image_align)表示相对文字的位置，[后两个值](http://www.w3school.com.cn/tiy/t.asp?f=html_image_float)表示浮动（个人觉得也是相对位置）。\
图片使用"height" 和 "width" 属性的值来控制其宽高。想对图片加以描述可以使用[alt="向左转"](http://www.w3school.com.cn/tiy/t.asp?f=html_image_alt) 属性。\
图片可以像a标签一样设置点击属性[src="#"](http://www.w3school.com.cn/tiy/t.asp?f=html_image_link)。\
若想点击图片的某一块区域并处理事件，那么就可以使用[图像映射](http://www.w3school.com.cn/tiy/t.asp?f=html_areamap)。

> 10.HTML 背景实例

* 一个[好的配色](http://www.w3school.com.cn/tiy/t.asp?f=html_back_good)能是用户使用更舒适。\
一个[不适合的配置](http://www.w3school.com.cn/tiy/t.asp?f=html_back_bad)使页面中的文字难于阅读。\
[可用性强的背景图像](http://www.w3school.com.cn/tiy/t.asp?f=html_back_img)不失为一种很好的办法。

> 11.HTML 样式 (style) 实例

* 样式可以直接写在标签中，在学习W3C过程中，联系的代码都优先将样式写在[标签中](http://www.w3school.com.cn/tiy/t.asp?f=html_linknoline)。\
但写在标签中的样式有个天然的缺陷，不方便复用。\
所以在时机开发中可以将样式添加到标签[head](http://www.w3school.com.cn/tiy/t.asp?f=html_style)中。\
当然，实际项目开发中也是作为[外部样式](http://www.w3school.com.cn/tiy/t.asp?f=html_link)引入的。

> 12.HTML 头部 (head) 实例

* 头部实例介绍的很少。\
W3C中只介绍了[文档的标题](http://www.w3school.com.cn/tiy/t.asp?f=html_title)，标题只会显示在浏览器标签中。\
还介绍了一个估计不太常用的东西[一个 target，所有的链接](http://www.w3school.com.cn/tiy/t.asp?f=html_base)。

> 13.HTML 元信息 (meta) 实例

* Meta 元素中的信息可以描述 [HTML 文档](http://www.w3school.com.cn/tiy/t.asp?f=html_meta)，
[关键词](http://www.w3school.com.cn/tiy/t.asp?f=html_keywords)，
[重定向](http://www.w3school.com.cn/tiy/t.asp?f=html_redirect)。\
Meta 元素的作用是提供文档的元信息。大多数情况下，meta 元素用来提供与浏览器或者搜索引擎相关的信息，比方说描述文档的内容等等。
对于Meta元素的更多了解[点这里](http://www.w3school.com.cn/html/html_meta.asp)。

> 14.HTML 脚本 (Script) 实例

* 这里只是简单的介绍了html插入一个[简单的脚本](http://www.w3school.com.cn/tiy/t.asp?f=html_script)。若浏览器不支持这个脚本
运行就使用[noscript](http://www.w3school.com.cn/tiy/t.asp?f=html_noscript)标签。实际使用中没看到谁使用这个标签，看来大家都不怎么关心细节。







