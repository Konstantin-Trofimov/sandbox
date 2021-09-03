<template>
    <calendar :gap="{gap: '5vw'}"/>
</template>

<script>
import Calendar from '@/components/Calendar.vue'

export default {
  name: 'Home',
  components: {
      Calendar
	}
}
</script>
