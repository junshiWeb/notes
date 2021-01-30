

|                                                      |                                                |
| ---------------------------------------------------- | ---------------------------------------------- |
| [Line](https://v-charts.js.org/#/en/line)            | [折线图](https://v-charts.js.org/#/line)       |
|                                                      |                                                |
| [Histogram](https://v-charts.js.org/#/en/histogram)  | [柱状图](https://v-charts.js.org/#/histogram)  |
|                                                      |                                                |
| [Bar](https://v-charts.js.org/#/en/bar)              | [条形图](https://v-charts.js.org/#/bar)        |
|                                                      |                                                |
| [Pie](https://v-charts.js.org/#/en/pie)              | [饼图](https://v-charts.js.org/#/pie)          |
|                                                      |                                                |
| [Ring](https://v-charts.js.org/#/en/ring)            | [环图](https://v-charts.js.org/#/ring)         |
|                                                      |                                                |
| [Waterfall](https://v-charts.js.org/#/en/waterfall)  | [瀑布图](https://v-charts.js.org/#/waterfall)  |
|                                                      |                                                |
| [Funnel](https://v-charts.js.org/#/en/funnel)        | [漏斗图](https://v-charts.js.org/#/funnel)     |
|                                                      |                                                |
| [Radar](https://v-charts.js.org/#/en/radar)          | [雷达图](https://v-charts.js.org/#/radar)      |
|                                                      |                                                |
| [Map](https://v-charts.js.org/#/en/map)              | [地图](https://v-charts.js.org/#/map)          |
|                                                      |                                                |
| [Sankey](https://v-charts.js.org/#/en/sankey)        | [桑基图](https://v-charts.js.org/#/sankey)     |
|                                                      |                                                |
| [Heatmap](https://v-charts.js.org/#/en/heatmap)      | [热力图](https://v-charts.js.org/#/heatmap)    |
|                                                      |                                                |
| [Scatter](https://v-charts.js.org/#/en/scatter)      | [散点图](https://v-charts.js.org/#/scatter)    |
|                                                      |                                                |
| [Candle](https://v-charts.js.org/#/en/candle)        | [K线图](https://v-charts.js.org/#/candle)      |
|                                                      |                                                |
| [Gauge](https://v-charts.js.org/#/en/gauge)          | [仪表盘](https://v-charts.js.org/#/gauge)      |
|                                                      |                                                |
| [Tree](https://v-charts.js.org/#/en/tree)            | [树图](https://v-charts.js.org/#/tree)         |
|                                                      |                                                |
| [Liquidfill](https://v-charts.js.org/#/en/wordcloud) | [水球图](https://v-charts.js.org/#/liquidfill) |
|                                                      |                                                |
| Wordcloud                                            | [词云图](https://v-charts.js.org/#/wordcloud)  |
|                                                      |                                                |



基本属性：

| 配置项              | 简介                                                         | 类型           | 默认值 |
| ------------------- | ------------------------------------------------------------ | -------------- | ------ |
| data                | 数据，[参考文档](https://v-charts.js.org/#/data)             | object         | -      |
| settings            | 配置项                                                       | object         | -      |
| width               | 宽度                                                         | string         | auto   |
| height              | 高度                                                         | string         | 400px  |
| events              | 事件绑定，[参考文档](https://v-charts.js.org/#/event)        | object         | -      |
| init-options        | init 附加参数，[参考文档](http://echarts.baidu.com/api.html#echarts.init) | object         | -      |
| tooltip-visible     | 是否显示提示框                                               | boolean        | true   |
| legend-visible      | 是否显示图例                                                 | boolean        | true   |
| theme               | 自定义主题                                                   | object         | -      |
| theme-name          | 自定义主题名称                                               | string         | -      |
| judge-width         | 是否处理生成图表时的宽度问题                                 | boolean        | false  |
| width-change-delay  | 容器宽度变化的延迟                                           | number         | 300    |
| resizeable          | 是否处理窗口 resize 事件                                     | boolean        | true   |
| cancel-resize-check | 是否禁用 resize 时的容器检测                                 | boolean        | false  |
| resize-delay        | 窗口 resize 事件回调的延迟                                   | number         | 200    |
| change-delay        | 属性修改触发图表重绘回调的延迟                               | number         | 0      |
| set-option-opts     | echarts setOption 的第二个参数, [参考文档](http://echarts.baidu.com/api.html#echartsInstance.setOption) | boolean object | true   |
| not-set-unchange    | 未发生变化时不参加 setOption 的属性                          | array          | -      |
| log                 | 在控制台打印内部生成的echarts options                        | boolean        | false  |

增加表示元素的属性

