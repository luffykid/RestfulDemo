<template>
  <div class="hello">
    <el-tabs type="border-card">
      <el-tab-pane label="Core Docs">
        <a
          href="https://vuejs.org"
          target="_blank"
        >
          Core Docs
        </a>
      </el-tab-pane>
      <el-tab-pane label="Forum">
        <a
          href="https://forum.vuejs.org"
          target="_blank"
        >
          Forum
        </a>
      </el-tab-pane>
      <el-tab-pane label="Community Chat">
        <a
          href="https://chat.vuejs.org"
          target="_blank"
        >
          Community Chat
        </a>
      </el-tab-pane>
      <el-tab-pane label="Twitter">
        <a
          href="https://twitter.com/vuejs"
          target="_blank"
        >
          Twitter
        </a>
      </el-tab-pane>
      <br>
      <el-tab-pane label="Docs for This Template">
        <a
          href="http://vuejs-templates.github.io/webpack/"
          target="_blank"
        >
          Docs for This Template
        </a>
      </el-tab-pane>
    </el-tabs>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
