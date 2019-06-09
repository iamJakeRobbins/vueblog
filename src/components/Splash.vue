<template lang="html">
	<div id="splash">
		<Header/>
		<h1> {{title}}</h1>
		<router-link to="/blog">
			<h2>Blog</h2>
		</router-link>
		<Footer/>
	</div>

</template>

<script>
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';
import Blog from '@/views/Blog.vue';
export default {
	data: function() {
		return {
			title: 'Landing Page Test'
		}
	},
	components: {
		Header,
		Footer,
		Blog,
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
