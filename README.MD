# vue-page

> Vue页面导航解决方案
<ol>
<li>能完美支持浏览器的历史管理，能顺利前进与后退；</li>
<li>完美支持多级菜单，并能设置顶层功能的默认视图；</li>
<li>每个组件都可以对应到一个唯一的地址，加强了视图的复用；</li>
<li>能支持组件的动态刷新，在同一个组件上进行操作后，点击菜单依旧可以刷新此组件；</li>
<li>根据用户的操作过程，能自动生成访问路径，并支持快速切换，参见Window 7文件浏览器；</li>
<li>能快速解析参数，并能创建REST风格的访问路径；</li>
<li>支持模式窗口、路径引用、全屏模式、页面嵌入等多种方式引用视图；</li>
<li>支持路径上下文自动添加、统一切换功能；</li>
<li>提供后退按钮组件，自动切换到前一个视图；</li>
<li>不存在的地址能导向到错误页面；</li>
</ol>

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

需要更详细地了解Vue编译工具，可参见 [webpack](https://github.com/vuejs-templates/webpack#vue-webpack-boilerplate) 与 [vue-loader](http://vuejs.github.io/vue-loader).
