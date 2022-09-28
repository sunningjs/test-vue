<template>
  <div id="app" @click="change">
    {{data}}
  </div>
</template>

<script>

export default {
  name: 'App',
  data() {
    return {
      data: '123'
    }
  },
  methods: {
    change() {
      this.data = '456'
    }
  }
}
</script>

<style>

</style>
