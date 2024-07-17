<!-- eslint-disable vue/html-self-closing -->
<template>
	<div
		data-aos="fade-up"
		class="min-h-screen bg-gray-100 dark:bg-gray-900 text-gray-800 dark:text-gray-200 p-4 md:p-8 rounded-xl"
	>
		<div class="flex justify-between">
			<router-link class="btn btn-warning w-100" to="/projects"
				>Back To Projects</router-link
			>
			<a
				class="btn bg-[#2b3d4f] text-white hover:bg-[#e89e1d]"
				href="https://thewebmasters.online/"
				target="_blank"
				>Live Version</a
			>
		</div>
		<div class="bg-[#e0ffff] block h-[1px] my-8"></div>
		<div class="max-w-4xl mx-auto">
			<div class="flex flex-wrap flex-row-reverse justify-evenly">
				<h2
					data-aos="fade-up"
					class="text-3xl md:text-5xl font-bold mb-4 text-center self-center"
				>
					Gotta Go Ottawa
				</h2>
				<img
					data-aos="fade-up"
					src="/assets/projects/gotta_go/logo.svg"
					alt="Screenshot of the React Contact Book application"
					class="w-[80%] md:w-1/2 lg:w-1/6 h-auto rounded-lg mb-4 md:mb-0"
				/>
			</div>

			<p class="text-base md:text-lg my-4">
				Gotta Go Ottawa's new website was my capstone project in the final
				semester of my Interactive Media Program. As the team second in a group
				of five, I played a key role in revamping the information architecture
				and redesigning the entire website. This project is ongoing and is
				expected to fully launch in fall 2024.
			</p>
			<h3 class="text-xl md:text-3xl font-semibold mb-2">Website Features</h3>
			<div class="flex flex-wrap justify-evenly mt-8">
				<ul
					class="grid grid-cols-1 md:grid-cols-6 *:col-span-2 gap-y-3 gap-x-4 my-2"
				>
					<li
						class="w-100 text-center self-center bg-white text-black p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
					>
						WordPress
					</li>
					<li
						class="w-100 text-center self-center bg-white text-black p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
					>
						Elementor
					</li>
					<li
						class="w-100 text-center self-center bg-white text-black p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
					>
						PHP
					</li>
					<li
						class="w-100 text-center self-center bg-white text-black p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
					>
						Tailwind
					</li>
					<li
						class="w-100 text-center self-center bg-white text-black p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
					>
						Contact Form 7
					</li>
					<li
						class="w-100 text-center self-center bg-white text-black p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
						s
					>
						Aria Standards
					</li>
				</ul>
				<img
					class="md:max-w-[400px] bg-white p-3 rounded-xl"
					src="/assets/projects/gotta_go/findtoilets.svg"
					alt=""
				/>
			</div>
		</div>
	</div>
</template>
