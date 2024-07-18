<template>
	<!-- Project Section -->
	<section
		id="projects"
		class="mt-10"
		aria-labelledby="projects_heading"
		data-aos="fade-up"
		data-aos-duration="1000"
	>
		<h2 id="projects_heading" class="text-3xl font-bold mb-4">My Projects</h2>
		<div>
			<p class="md:w-[60%] text-justify">
				Welcome to My Portfolio! Below, you'll find a collection of the projects
				I am most proud of. Each project showcases a variety of skills, ranging
				from web design to development and everything in between.
			</p>
			<div
				class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-4 p-3 mt-2"
			>
				<router-link
					data-aos="fade-up"
					data-aos-duration="3000"
					class="btn bg-[#2b3d4f] text-white hover:bg-[#e89e1d]"
					to="/projects/contactbook"
					>React Contact Book</router-link
				>
				<router-link
					data-aos="fade-up"
					data-aos-duration="3000"
					class="btn bg-[#2b3d4f] text-white hover:bg-[#e89e1d]"
					to="/projects/password_generator"
					>Password Generator</router-link
				>
				<router-link
					data-aos="fade-up"
					data-aos-duration="3000"
					class="btn bg-[#2b3d4f] text-white hover:bg-[#e89e1d]"
					to="/projects/pomodoro_timer"
					>Pomodoro Timer</router-link
				>
				<router-link
					data-aos="fade-up"
					data-aos-duration="3000"
					class="btn bg-[#2b3d4f] text-white hover:bg-[#e89e1d]"
					to="/projects/gotta_go_ottawa"
					>Gotta Go Ottawa</router-link
				>
				<router-link
					class="btn bg-[#2b3d4f] text-white hover:bg-[#e89e1d]"
					to="/projects/the_county_cooperage"
					data-aos="fade-up"
					data-aos-duration="3000"
					>The County Cooperage</router-link
				>
				<a
					class="btn bg-[#2b3d4f] text-white hover:bg-[#e89e1d]"
					href="https://github.com/jesse-gauthier"
					data-aos="fade-up"
					data-aos-duration="3000"
					referrerpolicy=""
					target="_blank"
					>Check Github For Active Projects</a
				>
			</div>
		</div>
	</section>
</template>
<script setup>
useSeoMeta({
	title: 'Projects',
	ogTitle: 'Jesse Gauthier',
})
</script>
