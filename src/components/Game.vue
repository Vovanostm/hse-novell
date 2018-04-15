<template>
  <div>
    <div
        v-if="room==='Begin'"
    >
        <begin></begin>
    </div>
  </div>
</template>
<script>
import Begin from './rooms/Begin'
export default {
  name:'Game',
  components: {
      Begin
  },
  data () {
      return{
        room:'Begin'
      }
  }
}
</script>

