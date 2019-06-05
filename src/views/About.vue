<template>
  <div id="about">
		<Header/>
    <h1>This is an about page</h1>
  </div>
</template>

<script>
import Header from '@/components/Header.vue';

export default {
  name: 'home',
  components: {
		Header,
  }
}
</script>

<style media="screen">
#about{
	height: 100vh;
	background-image: url('../assets/splash.jpg');
	background-repeat: no-repeat;
	background-size: 100vw 100vh;
	color: white;
}
</style>
