html 常见头部

meta：元

information：信息

charset： 字符集

| 属性                                                         | 值        | 描述                                       |
| :----------------------------------------------------------- | :-------- | :----------------------------------------- |
| [content](https://www.w3school.com.cn/tags/tag_meta.asp#meta_prop_content) | some_text | 定义与 http-equiv 或 name 属性相关的元信息 |
| 内容                                                         | 一些 文本 |                                            |

```
<meta http-equiv="Content-Type" content="text/html; charset=gb2312" />
```

| 属性                                                         | 值                                                        | 描述                                |
| :----------------------------------------------------------- | :-------------------------------------------------------- | :---------------------------------- |
| [http-equiv](https://www.w3school.com.cn/tags/tag_meta.asp#meta_prop_http-equiv) | content-type, expires, refresh, set-cookie                | 把 content 属性关联到 HTTP 头部。   |
|                                                              | 内容类型，期限，更新，设置 缓存-饼干                      |                                     |
| [name](https://www.w3school.com.cn/tags/tag_meta.asp#meta_prop_name) | author, description, keywords, generator, revised, others | 把 content 属性关联到一个名称。     |
| 名字，名称                                                   | 作者， 描述，按键，发生器（生产者），修改，其他人         |                                     |
| [scheme](https://www.w3school.com.cn/tags/tag_meta.asp#meta_prop_scheme) | some_text                                                 | 定义用于翻译 content 属性值的格式。 |
| 组合，计划                                                   |                                                           |                                     |



input 常用属性

| 属性                                                         | 值                                                           | 描述                                                         |
| :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| [accept](https://www.runoob.com/tags/att-input-accept.html)  | audio/* video/* image/* *MIME_type*                          | 规定通过文件上传来提交的文件的类型。 (只针对type="file")     |
| 接收，承认                                                   | 声音/ 视频/图片                                              |                                                              |
| [align](https://www.runoob.com/tags/att-input-align.html)    | left right top middle bottom                                 | 不用了                                                       |
| 排列                                                         | 左边的，右边的，上面的，中间的，下面的                       |                                                              |
| [alt](https://www.runoob.com/tags/att-input-alt.html)        | *text*                                                       | 定义图像输入的替代文本。 (只针对type="image")                |
|                                                              | 文本                                                         |                                                              |
| [autocomplete](https://www.runoob.com/tags/att-input-autocomplete.html)**New** | on off                                                       | autocomplete 提交你的表单内容，下次重新填充                  |
| 自动，完整的                                                 | 打开，关闭                                                   |                                                              |
| [autofocus](https://www.runoob.com/tags/att-input-autofocus.html)**New** | autofocus                                                    | 属性规定当页面加载时 <input> 元素应该自动获得焦点。          |
| 自动 焦点                                                    |                                                              |                                                              |
| [checked](https://www.runoob.com/tags/att-input-checked.html) | checked                                                      | checked 属性规定在页面加载时应该被预先选定的 <input> 元素。 (只针对 type="checkbox" 或者 type="radio") |
| 检查，选中                                                   |                                                              |                                                              |
| [disabled](https://www.runoob.com/tags/att-input-disabled.html) | disabled                                                     | disabled 属性规定应该禁用的 <input> 元素。                   |
| 不选中，失去能力                                             |                                                              |                                                              |
| [form](https://www.runoob.com/tags/att-input-form.html)**New** | *form_id*                                                    | form 属性规定 <input> 元素所属的一个或多个表单。             |
| [formaction](https://www.runoob.com/tags/att-input-formaction.html)**New** | *URL*                                                        | 属性规定当表单提交时处理输入控件的文件的 URL。(只针对 type="submit" 和 type="image") |
| 表单，活动，行动                                             |                                                              |                                                              |
| [formmethod](https://www.runoob.com/tags/att-input-formmethod.html)**New** | get post                                                     | 定义发送表单数据到 action URL 的 HTTP 方法。 (只适合 type="submit" 和 type="image") |
| 方法                                                         | 获得，邮件（加密）                                           |                                                              |
| [formtarget](https://www.runoob.com/tags/att-input-formtarget.html)**New** | _blank _self _parent _top *framename*                        | 规定表示提交表单后在哪里显示接收到响应的名称或关键词。(只适合 type="submit" 和 type="image") |
| 目标，指标                                                   |                                                              |                                                              |
| [height](https://www.runoob.com/tags/att-input-height.html)**New** | *pixels*                                                     | 规定 <input>元素的高度。(只针对type="image")                 |
| [list](https://www.runoob.com/tags/att-input-list.html)**New** | *datalist_id*                                                | 属性引用 <datalist> 元素，其中包含 <input> 元素的预定义选项。 |
| [max](https://www.runoob.com/tags/att-input-max.html)**New** | *number date*                                                | 属性规定 <input> 元素的最大值。                              |
| [maxlength](https://www.runoob.com/tags/att-input-maxlength.html) | *number*                                                     | 属性规定 <input> 元素中允许的最大字符数。                    |
| [min](https://www.runoob.com/tags/att-input-min.html)**New** | *number date*                                                | 属性规定 <input>元素的最小值。                               |
| [multiple](https://www.runoob.com/tags/att-input-multiple.html)**New** | multiple                                                     | 属性规定允许用户输入到 <input> 元素的多个值。                |
| [name](https://www.runoob.com/tags/att-input-name.html)      | *text*                                                       | name 属性规定 <input> 元素的名称。                           |
| [pattern](https://www.runoob.com/tags/att-input-pattern.html)**New** | *regexp*                                                     | pattern 属性规定用于验证 <input> 元素的值的正则表达式。      |
| 模式                                                         | 正则                                                         |                                                              |
| [placeholder](https://www.runoob.com/tags/att-input-placeholder.html)**New** | *text*                                                       | placeholder 属性规定可描述输入 <input> 字段预期值的简短的提示信息 。 |
| 地方，放置                                                   | holder：所有物                                               |                                                              |
| [readonly](https://www.runoob.com/tags/att-input-readonly.html) | readonly                                                     | readonly 属性规定输入字段是只读的。                          |
| 读取，只有，唯一                                             |                                                              |                                                              |
| [required](https://www.runoob.com/tags/att-input-required.html)**New** | required                                                     | 属性规定必需在提交表单之前填写输入字段。                     |
| 必需的                                                       |                                                              |                                                              |
| [size](https://www.runoob.com/tags/att-input-size.html)      | *number*                                                     | size 属性规定以字符数计的 <input> 元素的可见宽度。           |
| [src](https://www.runoob.com/tags/att-input-src.html)        | *URL*                                                        | src 属性规定显示为提交按钮的图像的 URL。 (只针对 type="image") |
| srouce：源文件                                               |                                                              |                                                              |
| [step](https://www.runoob.com/tags/att-input-step.html)**New** | *number*                                                     | step 属性规定 <input> 元素的合法数字间隔。                   |
| 步长                                                         |                                                              |                                                              |
| [type](https://www.runoob.com/tags/att-input-type.html)      | button checkbox color date datetime datetime-local email file hidden image month number password radio range reset search submit tel text time url week | type 属性规定要显示的 <input> 元素的类型。                   |
| 类型                                                         | button 按钮<br/>checkbox 复选框<br/>color 颜色<br/>date 日期<br/>datetime 日期和时间--<br/>datetime-local 本地时间<br/>email 邮件--<br/>file 文件<br/>hidden 隐藏<br/>image 图像，想象<br/>month 月<br/>number 数字<br/>password 密码<br/>radio 音频/单选<br/>range 范围<br/>reset 重置<br/>search 搜索<br/>submit 提交，主张，服从<br/>tel telephone 电话号码--<br/>text 文本<br/>time 时间小时<br/>url 全球统一资源定位器（uniform resource locator）--<br/>week 星期 |                                                              |
| [value](https://www.runoob.com/tags/att-input-value.html)    | *text*                                                       | 指定 <input> 元素 value 的值。                               |
| [width](https://www.runoob.com/tags/att-input-width.html)**New** | *pixels*                                                     | width 属性规定 <input> 元素的宽度。 (只针对type="image")     |



table 常用属性

| 属性                                                         | 值                                                           | 描述                                                         |
| :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| [align](https://www.runoob.com/tags/att-table-align.html)    | left center right                                            | HTML5 不支持。HTML 4.01 已废弃。 规定表格相对周围元素的对齐方式。 |
| [bgcolor](https://www.runoob.com/tags/att-table-bgcolor.html) | *rgb(x,x,x) #xxxxxx colorname*                               | HTML5 不支持。HTML 4.01 已废弃。 规定表格的背景颜色。        |
| [border](https://www.runoob.com/tags/att-table-border.html)  | 1 ""                                                         | 规定表格单元是否拥有边框。                                   |
| 边界，边框                                                   |                                                              |                                                              |
| [cellpadding](https://www.runoob.com/tags/att-table-cellpadding.html) | *pixels*                                                     | HTML5 不支持。规定单元边沿与其内容之间的空白。               |
| 单元格边框                                                   |                                                              |                                                              |
| [cellspacing](https://www.runoob.com/tags/att-table-cellspacing.html) | *pixels*                                                     | HTML5 不支持。规定单元格之间的空白。                         |
| 单元格间距                                                   |                                                              |                                                              |
| [frame](https://www.runoob.com/tags/att-table-frame.html)    | void above below hsides lhs rhs vsides box border            | HTML5 不支持。规定外侧边框的哪个部分是可见的。               |
| 框架，结构                                                   | void 空的<br/>above 多余<br/>below 在下面<br/>hsides 隐藏<br/>lhs 在左边<br/>rhs 在右边<br/>vsides 左右边框<br/>box 盒子<br/>border 边框 |                                                              |
| [rules](https://www.runoob.com/tags/att-table-rules.html)    | none groups rows cols all                                    | HTML5 不支持。规定内侧边框的哪个部分是可见的。               |
| 规则                                                         | none 没有<br/>groups 小组<br/>rows 一排<br/>cols 一列<br/>all 所有 |                                                              |
| [summary](https://www.runoob.com/tags/att-table-summary.html) | *text*                                                       | HTML5 不支持。规定表格的摘要。                               |
| 概要，总结                                                   |                                                              |                                                              |
| [width](https://www.runoob.com/tags/att-table-width.html)    | *pixels %*                                                   | HTML5 不支持。规定表格的宽度。                               |

