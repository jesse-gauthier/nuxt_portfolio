<template>
	<div class="flex flex-col gap-4 min-h-screen mx-w-screen">
		<MainHeader />
		<div class="inner-wrapper">
			<NuxtLayout>
				<NuxtPage />
			</NuxtLayout>
		</div>
		<MainFooter class="mt-auto" />
	</div>
</template>

<script setup>
import { onMounted } from 'vue'
import AOS from 'aos'
import 'aos/dist/aos.css'

onMounted(() => {
	const prefersReducedMotion = window.matchMedia(
		'(prefers-reduced-motion: reduce)'
	).matches

	if (!prefersReducedMotion) {
		AOS.init({
			duration: 3000,
			once: true,
		})
	}
})
</script>
