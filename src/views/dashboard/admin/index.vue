<template>
  <div class="dashboard-editor-container">
    <h1>
      Hello World,
      <div>
        This is {{$t('pages.title')}}
      </div>
    </h1>
  </div>
</template>

<script>
export default {
  name: 'dashboard-admin',
  components: {},
  data() {
    return {}
  },
  methods: {}
}
</script>

<style rel="stylesheet/scss" lang="scss" scoped>
.dashboard-editor-container {
    padding: 32px;
    background-color: rgb(240, 242, 245);
    .chart-wrapper {
        background: #fff;
        padding: 16px 16px 0;
        margin-bottom: 32px;
    }
}
</style>
