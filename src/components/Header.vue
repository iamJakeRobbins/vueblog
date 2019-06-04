<template lang="html">
  <div class="mainHeader">
		<h2>header text goes here</h2>
		<button type="button" name="button" @click='this.load'>click me</button>
  </div>
</template>

<script>
export default {
	methods: {
		load: function () {
			console.log('hello')
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
