

### 简介

[vue-admin-template](https://github.com/neveryielding/vue-admin-template)是基于[vue-element-admin](https://github.com/neveryielding/vue-element-admin)项目二次开发的后端管理系统脚手架，在此感谢该项目作者[PanJiaChen](https://github.com/PanJiaChen) ，在开发中，对该项目的代码加入了一些自己的元素，删除大部分在项目中用不到的组件，编写了部分通用代码以及组件，可作为实际项目开发参考，并改造了部分代码，采用了Ant Design风格改造了该项目的UI，UI风格参考 [Ant Design Pro](https://preview.pro.ant.design/#/dashboard/analysis)

### 支持环境
-   现代浏览器和 IE9 及以上（需要  [polyfills](https://ant.design/docs/react/getting-started-cn#%E5%85%BC%E5%AE%B9%E6%80%A7)）。
-   支持服务端渲染。
###  其他内容
-  [在线访问](http://www.stars21.cn/) <br/>
**component** 目录下编写了自己平时在项目中常用的几个组件 <br/>
	SearchBar -> 用于页表页面表格上面、查询 、新增以及其他功能日期宣增等封装的参数化配置组件；<br/>
	MLoading  -> 主要是用于数据加载，根据element-loading进行扩展；<br/>
	TableContain -> 在el-tab 在内容超出页高度的时候自动计算固定大小，超出在内容中滚动，由于监控了resize函数，在页面大小改变时tab的height会被重新计算；<br/>
**public** 目录下是基于页面封装通用的js模块<br/>
**mock**  模拟数据<br/>
	mock -> user.js 部分只是简单的实现了用户的增删查改，在UI上并没有体现，只是提供了实现方式;<br/>
**style**	 重写之前项目的大部分样式，具体风格参考Ant Design，修改了element-ui.scss部分组件样式，theme-black.css 自定义的主题样式，list-page-scss 根据项目需要编写的列表页面通用样式；<br/><br/>
    **欢迎大家给star，提issues，我每天会抽出一定的业余时间来更新项目，解决问题。**<br/>
    **目前还有很多模块待继续优化，后续部分会继续完善..................................<br/>**
### 项目截图
![enter image description here](http://chuantu.biz/t6/338/1530719430x-1404817706.png)
![enter image description here](http://chuantu.biz/t6/338/1530719456x-1404817706.png)
![enter image description here](http://chuantu.biz/t6/338/1530719491x-1404817706.png)
![enter image description here](http://chuantu.biz/t6/338/1530719491x-1404817706.png)
