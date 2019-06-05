<template>
  <div class="home">
		<Header/>
		<Splash/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Splash from '@/components/Splash.vue'
import Header from '@/components/Header.vue'

export default {
  name: 'home',
  components: {
    HelloWorld,
		Splash,
		Header,
  }
}
</script>
