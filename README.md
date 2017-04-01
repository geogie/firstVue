# first-vue

> first vue project

## Build Setup
#### 由于该项目没有用到eslint来检验代码格式，所以，初始化的时候不要用开启eslint，如果开启了会报错

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
## 总结
这个Webapp主要是两个页面 Home和Detail

Home：主页
Detail：详情页

HomeHeader：是主页的头部显示 主页
List：是单个item，提供主页形成list
DetailHeader：详情页的头部显示 返回、详情

Home 页面包含两部分 HomeHeader和List  HomeHeader提供home-header标签，List提供list标签
Detail 页面包含 DetailHeader DetailHeader提供detail-header标签

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
