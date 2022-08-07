<template>
  <div class="me">
    <HyunJi msg="I'm Hyunji"/>
    <ComponentBasic/>
  </div>
</template>

<script>
// @ is an alias to /src
import HyunJi from '@/components/HyunJi.vue'
import ComponentBasic from '@/components/ComponentBasic.vue'

export default {
  name: 'HyunjiView',
  components: {
    HyunJi,
    ComponentBasic
  }
}
</script>
