<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul>
    <h3>element</h3>
    <ul>
      <li> <a href="https://ncform.github.io/ncform/ncform-theme-elementui/index.html" target="_blank">ncform，一种令人愉悦的表单开发方式，仅需配置即可生成表单UI及其交互行为。</a></li>
      <li> <a href="https://github.com/" target="_blank">GitHub</a></li>
      <li> <a href="http://www.form-create.com/" target="_blank">form-create</a></li>
      <li> <a href="http://tools.xiaoyaoji.cn/" target="_blank">表单设计器vue-form-making</a></li>
      <li> <a href="https://github.com/jsonform/jsonform" target="_blank">表单生成jsonform</a></li>
      <li> <a href="https://avuejs.com/" target="_blank">表单生成avue</a></li>
      <li> <a href="https://cn.vuejs.org//" target="_blank">Vuejs渐进式JavaScrilit 框架</a></li>
      <li> <a href="https://element.eleme.cn/#/zh-CN" target="_blank">element基于 Vue 2.0 的桌面端组件库</a></li>
      <li> <a href="https://github.com/jquery-form/form" target="_blank">表单提交jquery-form</a></li>
      <li> <a href="http://es6.ruanyifeng.com/" target="_blank">ES6</a></li>
      <li> <a href="https://github.com/dream2023/vue-ele-form" target="_blank">基于element-ui的数据驱动表单组件vue-ele-form</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
