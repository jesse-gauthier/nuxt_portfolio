<template>
	<div class="flex justify-between">
		<router-link class="btn btn-sm btn-warning w-100" to="/projects">
			Back To Projects
		</router-link>
		<a
			class="btn btn-sm btn-warning w-100"
			:href="liveVersionLink"
			target="_blank"
		>
			Live Version
		</a>
	</div>
</template>

<script setup>
import { defineProps } from 'vue'

const props = defineProps({
	liveVersionLink: {
		type: String,
		required: true,
	},
})
</script>

<style scoped></style>
