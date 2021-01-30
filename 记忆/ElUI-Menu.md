- el-menu

|      | 参数                | 说明                                                         | 类型    | 可选值 | 默认值   |
| ---- | :------------------ | :----------------------------------------------------------- | :------ | :----- | :------- |
|      | mode                | 模式horizontal / vertical                                    | string  | h/v    | vertical |
|      | collapse            | 是否水平折叠收起菜单                                         | boolean | —      | false    |
|      | background-color    | 菜单的背景色（仅支持 hex 格式）                              | string  | —      | #ffffff  |
|      | text-color          | 菜单的文字颜色（仅支持 hex 格式）                            | string  | —      | #303133  |
|      | active-text-color   | 当前激活菜单的文字颜色（支持 hex 格式）                      | string  | —      | #409EFF  |
|      | default-active      | 当前激活菜单的 index                                         | string  | —      | —        |
|      | default-openeds     | 当前打开的 sub-menu 的 index 的数组                          | Array   | —      | —        |
| x    | unique-opened       | 是否只保持一个子菜单的展开                                   | boolean | —      | false    |
| x    | menu-trigger        | 子菜单打开的触发方式 hover / click                           | string- | h/c    | hover    |
|      | router              | 是否使用 vue-router 的模式<br />以 index 作为 path 进行路由跳转 | boolean | —      | false    |
| x    | collapse-transition | 是否开启折叠动画                                             | boolean | —      | true     |



- el-submenu

| 参数                  | 说明                                                         | 类型        | 可选值 | 默认值                                 |
| :-------------------- | :----------------------------------------------------------- | :---------- | :----- | :------------------------------------- |
| index                 | 唯一标志                                                     | string/null | —      | null                                   |
| popper-class          | 弹出菜单的自定义类名                                         | string      | —      | —                                      |
| show-timeout          | 展开 sub-menu 的延时                                         | number      | —      | 300                                    |
| hide-timeout          | 收起 sub-menu 的延时                                         | number      | —      | 300                                    |
| disabled              | 是否禁用                                                     | boolean     | —      | false                                  |
| popper-append-to-body | 是否将弹出菜单插入至 body 元素<br />在菜单的定位出现问题时，可尝试修改该属性 | boolean     | —      | 一级子菜单：true / 非一级子菜单：false |

- el-menu-item

| 参数     | 说明                | 类型    | 可选值 | 默认值 |
| :------- | :------------------ | :------ | :----- | :----- |
| index    | 唯一标志            | string  | —      | —      |
| route    | Vue Router 路径对象 | Object  | —      | —      |
| disabled | 是否禁用            | boolean | —      | false  |