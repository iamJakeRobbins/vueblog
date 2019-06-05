<template>
  <div class="home">
		<Header/>
		<Splash/>
		<div class="alert alert-success alert-dismissible fade show" role="alert">
  With Bootstrap!
  <button type="button" class="close" data-dismiss="alert" aria-label="Close">
    <span aria-hidden="true">&times;</span>
  </button>
</div>
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
