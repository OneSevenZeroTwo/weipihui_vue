<template>
	<div>
		<xheader></xheader>
		<xbillmainl></xbillmainl>
		<xfoot></xfoot>
	</div>
</template>
<script>
	import xheader from "../xheader.vue";
	import xbillmainl from "../xbillmainl.vue";
	import xfoot from "../xfoot.vue";
	export default {
		components: {
			xheader,
			xbillmainl,
			xfoot
		}
	}
</script>
<style scoped>
	
</style>