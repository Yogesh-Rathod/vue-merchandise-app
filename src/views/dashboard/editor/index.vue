<template>
  <div class="dashboard-editor-container">
  </div>
</template>

<script>
import { mapGetters } from 'vuex'
import PanThumb from '@/components/PanThumb'
import GithubCorner from '@/components/GithubCorner'

export default {
  name: 'dashboard-editor',
  components: { PanThumb, GithubCorner },
  data() {
    return {
      emptyGif:
        'https://wpimg.wallstcn.com/0e03b7da-db9e-4819-ba10-9016ddfdaed3'
    }
  },
  computed: {
    ...mapGetters(['name', 'avatar', 'roles'])
  }
}
</script>

<style rel="stylesheet/scss" lang="scss" scoped>
.dashboard-editor-container {
    background-color: #e3e3e3;
    min-height: 100vh;
    padding: 50px 60px 0px;
}
</style>
