[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[PrimeNG homepage](http://www.primefaces.org/primeng)

[Camc PrimeNG homepage](https://github.com/w21976169/camc-primeng)

## Camc PrimeNG

由于项目使用的 Chrome v49 版本，不支持 html5，其中对 html 的一些特性不支持；
所以在 Primeng@7.1.3 做了一些扩展；

### Bug List

- 部分组件搜索不支持中文问题 (Dropdown, Multiselect, Listbox, OrderList, PickList, Tree)

### Npm Install

```
npm install camc-primeng --save
npm install primeicons --save
```

### Package json dependencies.

```
"dependencies": {
  //...
  "camc-primeng": "^7.0.0",
  "primeicons": "^1.0.0"
},
```

### Angular json styles

在 angular.json 中添加 样式

```
"styles": [
  "node_modules/camc-primeng/resources/themes/nova-light/theme.css",
  "node_modules/camc-primeng/resources/primeng.min.css",
  "node_modules/primeicons/primeicons.css",
  //...
],
```
