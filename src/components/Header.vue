<template lang="html">
  <div class="mainHeader">
		<div id="nav">
			<!-- <router-link to="/new"> Add A Post</router-link> -->
    </div>
		<div id='home'>
			<!-- <img src="../assets/arrow-down-right.svg" alt="">
			<i class="fas fa-arrow-right"></i> -->
			<router-link to="/" class="navLink">
				<h2>Name of Site (doubles as a link to home!)</h2>
			</router-link>
			<router-link to="/about" class="navLink"> About</router-link>
		</div>

  </div>
</template>

<script>
export default {
	methods: {
		load: function () {
			console.log(this.$router)
			this.$router.go(this.$router.options.routes[0])
		}

	}
}
</script>

<style lang="css" scoped>

.mainHeader {
	height: 10vh;
	/* background-color: teal; */
}

.navLink {
	color: white;
	text-decoration: none;
}
</style>
