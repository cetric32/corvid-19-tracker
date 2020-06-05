<template>
  <div class="hello">
    <div class="container">
       <img src="@/assets/Corvid-19.png"  class="mx-auto d-block" alt="Corvid-19 logo Image">
       <Countries />
    </div>
  </div>
</template>

<script>
import Countries from '@/components/home/Countries.vue'

export default {
  name: 'Home',
  props: {
    msg: String
  },
  components: {
    Countries
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
img{
  width: 300px;
}

</style>
