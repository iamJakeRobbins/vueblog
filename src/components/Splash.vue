<template lang="html">
	<div id="splash">
		<Header/>
		<h1> {{title}}</h1>
		<Footer/>
	</div>

</template>

<script>
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';
export default {
	data: function() {
		return {
			title: 'Landing Page Test'
		}
	},
	components: {
		Header,
		Footer,
	}
}
</script>

<style lang="css" scoped>
#splash{
	height: 100vh;
	background-image: url('../assets/splash.jpg');
	background-repeat: no-repeat;
	background-size: 100vw 100vh;
	color: white;
}
</style>
