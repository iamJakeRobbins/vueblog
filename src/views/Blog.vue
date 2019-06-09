<template lang="html">
	<div id="blog">
		<h1>route working</h1>
		<Summaries/>
	</div>

</template>

<script>
import Summaries from '@/components/Summary.vue';
export default {
	data: function() {
		return {
			posts: {

			}
		}
	},
	components: {
		Summaries,
	}
}

</script>

<style lang="css" scoped>
#blog{
	height: 100vh;
	background-image: url('../assets/splash.jpg');
	background-repeat: no-repeat;
	background-size: 100vw 100vh;
	color: white;
}
</style>
