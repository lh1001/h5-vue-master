<template>
 	<div class="container">
 		<Login></Login>
 		<Shadow></Shadow>
 	</div>
</template>

<script>
	import Login from '../layouts/Login.vue'
	import Shadow from '../components/shadow.vue'
	export default {
		components: {
		 	Login,
		 	Shadow,
		}
	}
</script>

<style scoped>
	.container{
		
	}
</style>