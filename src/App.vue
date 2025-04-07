<script>
export default {
  data() {
    return {
      info: 'Title',
      someInfo: 'Anons'
    }
  },
  methods: {
    userData(data = 'New Text') {
      this.info = data
    }
  }
}
</script>

<template>
  <h1>{{info}}</h1>
  <button type="button" @mouseenter="userData('sdwefwf')">Отправить</button>
</template>

<style scoped>    
h1 {
  font-weight: lighter;
}
</style>
