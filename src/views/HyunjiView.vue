<template>
  <div class="me">
    <HyunJi msg="I'm Hyunji"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HyunJi from '@/components/HyunJi.vue'

export default {
  name: 'HyunjiView',
  components: {
    HyunJi
  }
}
</script>
