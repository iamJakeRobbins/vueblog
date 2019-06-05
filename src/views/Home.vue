<template>
  <div class="home">
		<Splash/>
  </div>
</template>

<script>
// @ is an alias to /src
import Splash from '@/components/Splash.vue'
import Header from '@/components/Header.vue'

export default {
  name: 'home',
  components: {
		Splash,
		Header,
  }
}
</script>
<style media="screen">
</style>
