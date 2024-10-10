基于 ant-design-vue 1.7.8 版本开发,主要解决 table 固定列,滚动不对齐问题

源码属于 ant-design-vue 团队

开源协议以 ant-design-vue 团队制定为准


先卸载项目原来装的ant-design-vue

然后执行`npm install ant-design-vue-v1-table_scroll`,安装修改后的插件.

然后在项目文件全区搜索ant-design-vue,对应替换成ant-design-vue-v1-table_scroll.

如果原来main.js有
```
import "ant-design-vue-v1-table_scroll/dist/antd.less";
```
要替换成
```
import 'ant-design-vue-v1-table_scroll/dist/antd.css';
```
