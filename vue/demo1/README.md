# demo

> A simple Vue.js project

## Build Setup

``` bash
##vue简单例子开发步骤：
# 1.新建普通html
# 2.引入vue库
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
# 3.加入div，用于展现信息
<div id="app">
  <p>{{ message }}</p>
</div>
# 4.在div后加入vue声明与初始化（不能在div前，否则会提示找不到对应的组件）
<script type="text/javascript">
new Vue({
  el: '#app',
  data: {
    message: 'Hello Vue.js!'
  }
});
</script>
# 5.直接通过浏览器打开index.html即可
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).
