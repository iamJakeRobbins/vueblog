<template lang="html">
  <div class="mainHeader">
		<div id='home'>
			<div class="headerBox">
				<div class="menu">
				side
				</div>
				<div class="headerTitle">
					<router-link to="/" class="navLink">
						<h2>Name of Site (doubles as a link to home!)</h2>
					</router-link>
				</div>
		</div>
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

.headerBox {
	display: flex;
	justify-content: space-between;
}

.navLink {
	color: white;
	text-decoration: none;
}

.headerTitle {
	padding-top: 1vh;
	padding-right: 1vw;
	text-align: right;
}

.menu {
	padding-top: 1vh;
	padding-left: 1vw;
}
</style>
