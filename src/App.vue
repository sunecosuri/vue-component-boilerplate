<template>
  <div>
    {{msg}}
    <child></child>
  </div>
</template>

<script>
import Child from './components/Child.vue'
export default {
  components: {
    Child
  },
  data() {
    return { msg: '親 コンポーネント' }
  }
}
</script>
