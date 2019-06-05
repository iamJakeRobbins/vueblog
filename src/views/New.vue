<template>
  <div id="new">
		<Header/>
		<div class="thing">
			<h3>Go Ahead, tell us a story</h3>
			
		</div>
  </div>
</template>

<script>
import Header from '@/components/Header.vue';

export default {
  name: 'new',
  components: {
		Header,
  }
}
</script>

<style media="screen">
	#new {
		height: 100vh;
		background-image: url('../assets/splash.jpg');
		background-repeat: no-repeat;
		background-size: 100vw 100vh;
		color: white;
	}
	.thing {
		border: 2px solid white;
		margin-left: 8vw;
		height: 80vh;
		width: 45vw;
	}
</style>
