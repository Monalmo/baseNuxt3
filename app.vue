<template lang="pug">
div
	h1 holooooo
	.comentario este es el comen tario
		| {{algo}}		
		.algoMas algoMas
			|	{{algo2}}
</template>

<script setup lang="ts">
import { ref } from 'vue'
const algo = ref('algooooooo')
const algo2 = ref({
	hh: 'd',
	gg: '3'
})
</script>

<style lang="sass" scoped>

h1
	color: red


.comentario
	color: blue
	.algoMas
		color: green
</style>
