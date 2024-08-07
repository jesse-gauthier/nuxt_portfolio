<!-- eslint-disable vue/html-self-closing -->
<template>
	<main class="flex flex-col gap-6">
		<div class="mt-12 flex flex-col gap-12">
			<!-- About Section -->
			<section
				id="about"
				class="grid grid-cols-1 lg:grid-cols-4 gap-4"
				aria-labelledby="tldr_title"
				data-aos="fade-up"
			>
				<div class="p-8 lg:col-span-2 flex justify-center flex-col gap-3">
					<img
						class="md:max-w-[70%] mx-auto rounded-lg"
						src="/assets/profile.jpg"
						alt=""
					/>
				</div>
				<div
					id="intro"
					class="flex justify-center flex-col lg:col-span-2 h-[100%] gap-8 border-[#2b3d4f40] border-4 py-3 px-5 rounded-lg"
				>
					<p class="text-black text-justify text-xl self-center">
						<span class="font-semibold text-2xl mt-1 block"
							>Hey, I'm <span class="orange-text">Jesse.</span></span
						>
						<br />
						I'm a dynamic and detail-oriented Web Developer with progressive
						experience in designing, developing, and maintaining robust websites
						and applications. I'm proficient in a variety of programming
						languages and frameworks, including JavaScript, Vue.js, React,
						MySQL, and PHP.
					</p>
					<div
						class="w-[15%] h-[1.8px] bg-[#2b3d4f] rounded-full mx-auto"
					></div>
					<p class="text-black text-justify text-xl self-center">
						Known for delivering client-focused solutions, enhancing user
						experiences, and driving business growth through innovative web
						strategies. I excel at collaborating with cross-functional teams to
						define project requirements, troubleshoot complex issues, and ensure
						the successful deployment of high-performance, scalable web
						solutions.
					</p>
					<router-link
						to="/contact"
						class="btn bg-[#2b3d4f] text-white hover:bg-[#e89e1d] w-fit mx-auto"
					>
						Work with me
					</router-link>
				</div>
			</section>
			<!-- Education Section -->
			<section
				id="education"
				class=""
				aria-labelledby="education_heading"
				data-aos="fade-up"
			>
				<h2 id="education_heading" class="text-4xl font-bold mb-7">
					Education
				</h2>
				<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-4">
					<article
						v-for="edu in education"
						:key="edu.program"
						class="p-8 blue-bg text-center w-full md:basis-1/2 flex flex-col justify-center rounded-lg"
						data-aos="fade-up"
					>
						<p v-if="edu.honours" class="font-bold text-xl m-0 orange-text">
							Dean's List Recipient
						</p>
						<p v-else class="font-bold text-xl m-0">Part Time</p>
						<h3 class="text-medium text-2xl self-center m-0">
							{{ edu.program }}
						</h3>
						<p class="text-lg m-0">{{ edu.institution }}</p>
						<p class="text-lg m-0">{{ edu.years }}</p>
					</article>
				</div>
			</section>
			<!-- Skills Section -->
			<section
				id="skills"
				class=""
				aria-labelledby="skills_heading"
				data-aos="fade-up"
			>
				<h2 id="skills_heading" class="text-4xl font-bold mb-7">My Stack</h2>
				<div class="flex flex-col gap-3 p-4 blue-bg rounded-lg shadow-md">
					<div>
						<h3 class="text-2xl font-bold my-3 orange-text">
							Programming Languages
						</h3>
						<ul class="flex flex-wrap gap-4 text-lg text-gray-700">
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								JavaScript
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								PHP
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								HTML
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								CSS
							</li>
						</ul>
					</div>
					<div>
						<h3 class="text-2xl font-bold my-3 orange-text">
							Frameworks & Libraries
						</h3>
						<ul class="flex flex-wrap gap-4 text-lg text-gray-700">
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								Node.js
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								Node Express
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								Vue.js
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								React.js
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								SASS
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								Tailwind CSS
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								Bootstrap
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								Express.js
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								Nuxt.js
							</li>
						</ul>
					</div>
					<div>
						<h3 class="text-2xl font-bold my-3 orange-text">
							Tools & Technologies
						</h3>
						<ul class="flex flex-wrap gap-4 text-lg text-gray-700">
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								WordPress
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								Shopify
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								MySQL
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								MongoDB
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								Rest API
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								Git
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								Docker
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								Webpack
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								Google Cloud
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								Plesk
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								cPanel
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								OOP
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								GitHub
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								Strapi
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								WCAG
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								NPM
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								Gulp
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								Responsive Design
							</li>
							<li
								data-aos="fade-up"
								class="bg-white p-2 rounded-md shadow-sm hover:bg-blue-100 transition duration-300"
							>
								Agile Methodologies
							</li>
						</ul>
					</div>
				</div>
			</section>
			<!-- Experience Section -->
			<section
				id="experience"
				class=""
				aria-labelledby="experience_heading"
				data-aos="fade-up"
			>
				<h2 id="experience_heading" class="text-4xl font-bold mb-7">
					Experience
				</h2>
				<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-4">
					<article data-aos="fade-up" class="mb-6 flex">
						<div class="p-8 blue-bg rounded-lg">
							<h3 class="text-3xl font-bold orange-text">
								Senior Web Developer | Shopify Developer
							</h3>
							<p class="text-xl my-2 font-bold">The County Cooperage</p>
							<p class="my-2 text-lg">May 2023 - Present</p>
							<p class="text-lg">
								Develop and implement web applications using HTML, CSS,
								JavaScript, jQuery, AJAX, and Shopify technologies to enhance
								user engagement and functionality. Debug cross-browser
								compatibility issues in IE, Chrome, Firefox, and Safari,
								ensuring a seamless user experience across major browsers.
								Research emerging technologies to identify new trends in web
								development, keeping projects up to date with the latest
								industry standards. Monitor page speed performance metrics
								through Google Analytics and Page Speed Insights, leading to
								optimized load times and better user retention.
							</p>
							<div>
								<hr class="my-4" />
								<h4 class="my-3 text-xl font-medium orange-text">
									Key Accomplishments:
								</h4>
								<ul class="list-disc list-outside *:text-lg">
									<li>
										Integrated third-party libraries such as jQuery, React.js,
										and Bootstrap to accelerate development time and enhance
										site features.
									</li>
									<li>
										Maintained websites to ensure content accuracy,
										accessibility, and security compliance standards, resulting
										in improved user trust and site integrity.
									</li>
									<li>
										Troubleshot coding errors utilizing browser debugging tools
										such as Firebug or Chrome DevTools, reducing issue
										resolution time and improving site performance
									</li>
									<li>
										Developed RESTful APIs that interacted with remote services,
										providing functionality such as payment gateways and 3rd
										party authentication systems, expanding service offerings.
									</li>
									<li>
										Designed And Development range of reuseable UI componenets
									</li>
									<li>
										Monitored Websites against user expereince metrics.
										Implemented Changes based on findings.
									</li>
								</ul>
							</div>
						</div>
					</article>
					<article data-aos="fade-up" class="mb-6 flex">
						<div class="p-8 blue-bg rounded-lg">
							<h3 class="text-3xl font-bold orange-text">
								Wordpress Developer | UI Researcher
							</h3>
							<p class="text-xl my-2 font-bold">GottaGo Ottawa</p>
							<p class="my-2 text-lg">Jan 2024 - Present</p>

							<p class="text-lg">
								Collaborated with a cross-functional team to define website
								objectives, aligning with the overall business strategy,
								resulting in a cohesive and effective online presence.
								Implemented SEO best practices and site optimization, boosting
								site performance and increasing visibility on search engines.
								Conducted user research and usability testing, refining design
								solutions based on insights and feedback, enhancing overall user
								experience. Managed version control and participated in code
								reviews, maintaining high-quality code standards, and ensuring
								team-wide code consistency.
							</p>
							<div>
								<hr class="my-4" />
								<h4 class="my-3 text-xl font-medium orange-text">
									Key Accomplishments:
								</h4>
								<ul class="list-disc list-outside *:text-lg">
									<li>
										Led the UX/UI design process, from concept to high-fidelity
										prototypes, enhancing usability and accessibility, and
										achieving a seamless responsive design
									</li>
									<li>
										Customized WordPress themes and plugins, balancing
										aesthetics and functionality, leading to improved user
										satisfaction and project success.
									</li>
									<li>
										Troubleshot coding errors utilizing browser debugging tools
										such as Firebug or Chrome DevTools, reducing issue
										resolution time and improving site performance
									</li>
									<li>
										Developed RESTful APIs that interacted with remote services,
										providing functionality such as payment gateways and 3rd
										party authentication systems, expanding service offerings.
									</li>
									<li>
										Designed And Development range of reuseable UI componenets
									</li>
									<li>
										Monitored Websites against user expereince metrics.
										Implemented Changes based on findings.
									</li>
									<li>
										Provided ongoing support and maintenance, resolving site
										performance and user experience issues, resulting in a more
										reliable and user-friendly website.
									</li>
								</ul>
							</div>
						</div>
					</article>
				</div>
			</section>
			<ContactForm data-aos="fade-up" class="w-[fit-content] mt-0" />
		</div>
	</main>
</template>

<script setup>
useSeoMeta({
	title: 'Jesse Gauthier',
	ogTitle: 'Jesse Gauthier',
})

const education = [
	{
		program: 'Interactive Media Design',
		institution: 'Algonquin College',
		years: '2022-2024',
		honours: 'true',
	},
	{
		program: 'Web Development and Internet Applications',
		institution: 'Fanshawe College',
		years: '2024-2026',
		honours: false,
	},
]
</script>
