# vue_vw

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


## dependencies && devDependencies

``` bash

# 安装 vux
npm install vux --save

# 安装 vux-loader  需要在build/webpack.base.conf.js 文件进行配置,具体[参阅文档](https://doc.vux.li/zh-CN/install/npm.html)
npm install vux-loader --save-dev

# 安装 less 和 less-loader 用于正确编译源码	
# 需要在build/webpack.base.conf.js的rules对象下添加{test: /\.less$/,loader: 'style-loader!css-loader!less-loader'}
npm install less less-loader --save-dev

# 安装 vw移动端适配所需模块 具体[参阅文档](https://www.w3cplus.com/mobile/vw-layout-in-vue.html)
npm i postcss-aspect-ratio-mini postcss-px-to-viewport postcss-write-svg postcss-cssnext postcss-viewport-units cssnano --S

# 安装 cssnano 完成后修改.postcssrc.js文件配置, 具体参阅上面文档
npm i cssnano-preset-advanced --save-dev



