

<template>
  <div>
    <calendar :gap="{gap: '5vw'}"/>
  </div>
</template>

<script>
import Calendar from './components/Calendar.vue'
  name: 'App'
  export default {
    components: {
      Calendar
	  },
  }

</script>

<style lang="scss">
* {
  text-align: center;
}

body {
  background-color: #112054;
}
</style>