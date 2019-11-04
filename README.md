# vxe-table-plugin-export

[![gitee star](https://gitee.com/xuliangzhan_admin/vxe-table-plugin-export/badge/star.svg?theme=dark)](https://gitee.com/xuliangzhan_admin/vxe-table-plugin-export/stargazers)
[![npm version](https://img.shields.io/npm/v/vxe-table-plugin-export.svg?style=flat-square)](https://www.npmjs.org/package/vxe-table-plugin-export)
[![npm downloads](https://img.shields.io/npm/dm/vxe-table-plugin-export.svg?style=flat-square)](http://npm-stat.com/charts.html?package=vxe-table-plugin-export)
[![gzip size: JS](http://img.badgesize.io/https://unpkg.com/vxe-table-plugin-export/dist/index.min.js?compression=gzip&label=gzip%20size:%20JS)](https://unpkg.com/vxe-table-plugin-export/dist/index.min.js)
[![npm license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/xuliangzhan/vxe-table-plugin-export/blob/master/LICENSE)

基于 [vxe-table](https://github.com/xuliangzhan/vxe-table) 表格的增强插件，支持导出 xlsx 等格式

## Installing

```shell
npm install xe-utils vxe-table vxe-table-plugin-export xlsx file-saver
```

```javascript
import Vue from 'vue'
import VXETable from 'vxe-table'
import VXETablePluginExport from 'vxe-table-plugin-export'

Vue.use(VXETable)
VXETable.use(VXETablePluginExport)
```

## License

MIT License, 2019-present, Xu Liangzhan
