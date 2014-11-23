<template>
  <!-- main view -->
  <div v-component="{{view}}" v-transition></div>
  <test-view></test-view>
</template>

<script>
  module.exports = {
    el: '#app',
    data: {
      view: 'test-view',
      params: {
        page: 1,
        userId: null,
        itemId: null
      }
    },
    components: {
      'test-view': require('./test.vue')
    }
  }
</script>
