<template>
	<div class="flex flex-col gap-4 min-h-screen">
		<MainHeader />
		<div class="inner-wrapper">
			<NuxtLayout>
				<NuxtPage />
			</NuxtLayout>
		</div>
		<MainFooter class="mt-auto" />
	</div>
</template>
