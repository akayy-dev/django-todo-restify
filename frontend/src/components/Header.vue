<template>
	<header>
		<h1>{{text}}</h1>
	</header>
</template>

<script>
export default {
	name: 'Header',
	props: {
		text: String
	}
}
</script>

<style scoped>
header {
	margin-top: 20px;
	margin-bottom: 20px;
	padding-left: 10px;
	display: flex;
}
</style>