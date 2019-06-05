<template lang="html">
  <div class="mainHeader">
		<div id="nav">
      <router-link to="/">Home </router-link> ||
      <router-link to="/about"> About</router-link> ||
			<router-link to="/new"> Add A Post</router-link>
    </div>
		<h2>header text goes here</h2>
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
</style>
