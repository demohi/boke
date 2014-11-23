<template>
  <div>{{test}}</div>
</template>

<script>

  module.exports = {
    replace: true,
    data: function () {
      return {
        test: 123
      }
    },
    compiled: function () {
      this.update();
    },
    methods: {
      update: function () {

      }
    }
  }
</script>
