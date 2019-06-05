<template lang="html">
  <div class="mainHeader">
		<div id="nav">
      <!-- <router-link to="/">Home </router-link> ||
      <router-link to="/about"> About</router-link> ||
			<router-link to="/new"> Add A Post</router-link> -->
    </div>

		<div id='home'>
			<img src="../assets/arrow-down-right.svg" alt="">
			<i class="fas fa-arrow-right"></i>
			<router-link to="/">
				<h2>Name of Site (doubles as a link to home!)</h2>
			</router-link>
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
	height: 10vw;
	background-color: teal;
}
h2 {
	padding: 0px;
}
#home {
	text-decoration: none;
	color: red;
}
</style>
