# vue-wx-public-demo

> A Vue.js project

### Use
```js
mounted() {
  this.$wxShare(
    {
      title: "", // 分享标题
      desc: "", // 分享描述
      link: location.href, // 分享链接
      imgUrl: `` // 分享图标
    },
    () => {
      // 分享成功的回调
    }
  );
}
```

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
