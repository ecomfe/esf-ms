ESF-MS
==============

**ESF-MS** 是基于 `管理端业务系统特点` 抽象的 `样式与布局框架`，依赖于 [LESS](http://github.com/cloudhead/less.js) 与 [EST](https://github.com/ecomfe/est)。
**ESF-MS** 的全称是：Enterprise Styling Framework for Manage System。

**ESF-MS** 的抽象包括常用部件的 `className`，相应的`html结构`，常变更样式点的`variable`。


使用
------

要使用 **ESF-MS** ，需要将 **EST** 和 **ESF-MS** 导入，在项目中建立自己的 `LESS` 文件，在该文件中import **EST** 和 **ESF-MS** 。

```css
@import "../../dep/est/1.0.0/src/all.less";
@import "../../dep/esf-ms/1.0.0/src/css/main.less";
```


文档
------

下面的文档详细说明了 **ESF-MS** 对管理端页面部件的支持：

- [页面](doc/page.md)
- [页头](doc/header.md)
- [列表](doc/list.md)
- [表单](doc/form.md)
- [版权](doc/copyright.md)



展示：一个典型的管理端系统
------

![Manage System](https://raw.github.com/ecomfe/esf-ms/master/doc/sys.png)

