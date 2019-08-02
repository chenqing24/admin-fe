# Admin-FE

基于`Majestic Admin`二开的响应式前端UI，涉及技术：

* Bootstrap framework
* SASS
* jQuery
* HTML5, and CSS

## 用法

1. git clone
2. `npm install`安装依赖
3. 游览器打开`index.html`，查看demo
4. 按需求改造

## 目录结构

```bash
admin-fe/
├── css/
├── fonts/
├── images/
├── js/
├── pages/
├── partials/
├── index.html
├── scss/
├── vendors/
├── gulpfile.js
├── package.json
├── CHANGELOG.md
```

## 自定义安装

```bash
# 安装js依赖，生成在node_modules/
npm install
# 安装gulp
npm install -g gulp-cli
# 启动http服务，打开预览页面，相关配置参考gulpfile.js
gulp serve
```
