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
				href="https://contactbook.jessegauthier.dev/"
				target="_blank"
				>Live Version</a
			>
		</div>
		<div class="bg-[#e0ffff] block h-[1px] my-8"></div>
		<div class="max-w-4xl mx-auto">
			<div class="flex flex-wrap flex-row-reverse justify-evenly">
				<h2
					data-aos-duration="3000"
					class="text-3xl md:text-5xl font-bold mb-4 text-center self-center"
				>
					React Contact Book
				</h2>
				<img
					src="/assets/projects/contact_book/contact_book3.png"
					alt="Screenshot of the React Contact Book application"
					class="w-[80%] md:w-1/2 lg:w-1/6 h-auto rounded-lg mb-4 md:mb-0"
				/>
			</div>

			<p class="text-base md:text-lg my-4">
				The React Contact Book application showcases the powerful capabilities
				of React, utilizing a custom Google FireStore Database for seamless data
				storage. This project was entirely developed by me as an academic
				assignment, where I achieved a perfect grade of 100%.
			</p>

			<div>
				<h3 class="text-xl md:text-2xl font-semibold mb-2">App Features</h3>
				<div class="md:flex justify-evenly gap-12">
					<ul
						class="grid grid-cols-1 md:grid-cols-6 *:col-span-2 gap-y-3 gap-x-4 my-2"
					>
						<li
							class="w-100 text-center self-center bg-white text-black p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
						>
							React
						</li>
						<li
							class="w-100 text-center self-center bg-white text-black p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
						>
							FireStore
						</li>
						<li
							class="w-100 text-center self-center bg-white text-black p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
						>
							Tailwind
						</li>
						<li
							class="w-100 text-center self-center bg-white text-black p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
						>
							Vite
						</li>
						<li
							class="w-100 text-center self-center bg-white text-black p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
						>
							Theme Toggle
						</li>

						<li
							class="w-100 text-center self-center bg-white text-black p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
						>
							Cloud Storage
						</li>
					</ul>
					<img
						src="/assets/projects/contact_book/contact_book1.png"
						alt="Another screenshot of the React Contact Book application"
						class="w-full md:w-1/2 h-auto rounded-lg"
					/>
				</div>
			</div>
		</div>
	</div>
</template>

<script setup></script>
