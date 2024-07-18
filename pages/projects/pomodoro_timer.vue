<!-- eslint-disable vue/html-self-closing -->
<template>
	<div
		data-aos="fade-up"
		class="min-h-screen bg-gray-100 dark:bg-gray-900 text-gray-800 dark:text-gray-200 p-4 md:p-8"
	>
		<div class="flex justify-between">
			<router-link class="btn btn-warning w-100" to="/projects"
				>Back To Projects</router-link
			>
			<a
				class="btn bg-[#2b3d4f] text-white hover:bg-[#e89e1d]"
				href="https://pomodorotimer.jessegauthier.dev/"
				target="_blank"
				>Live Version</a
			>
		</div>
		<div class="bg-[#e0ffff] block h-[1px] my-8"></div>
		<div class="max-w-4xl mx-auto">
			<div class="md:flex justify-evenly md:w-[50dvw] mx-auto">
				<img
					src="/assets/projects/timer/timer1.png"
					alt="Screenshot of the Pomodoro Timer application"
					class="w-full md:w-1/3 h-auto rounded-lg mb-4 md:mb-0"
				/>
				<h2
					class="text-2xl grow-1 md:text-3xl font-bold text-center self-center"
				>
					Pomodoro Timer
				</h2>
			</div>

			<p class="text-base md:text-lg my-4">
				Developed a productive Pomodoro Timer using pure JavaScript, featuring
				an intuitive user interface that helps manage work and break intervals
				efficiently. This tool is designed to enhance productivity by
				encouraging focused work sessions followed by short breaks.
			</p>

			<div>
				<h3 class="text-xl md:text-2xl font-semibold mb-2">App Features</h3>
				<ul
					class="grid grid-cols-1 md:grid-cols-6 *:col-span-2 gap-y-3 gap-x-4 my-2"
				>
					<li
						class="w-100 text-center self-center bg-white text-black p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
					>
						Vanilla JS
					</li>
					<li
						class="w-100 text-center self-center bg-white text-black p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
					>
						Customizable Work/Break Intervals
					</li>
					<li
						class="w-100 text-center self-center bg-white text-black p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
					>
						Visual and Audio Alerts
					</li>
					<li
						class="w-100 text-center self-center bg-white text-black p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
					>
						Progress Tracking
					</li>
					<li
						class="w-100 text-center self-center bg-white text-black p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
					>
						Theme Toggle
					</li>
				</ul>
			</div>
		</div>
	</div>
</template>
<script setup>
useSeoMeta({
	title: 'Pomodoro Timer - Jesse Gauthier',
	ogTitle: 'Jesse Gauthier',
})
</script>
