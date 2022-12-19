<template>
	<div class="bg-blue">
		<div class="wrapper flex justify-between items-center">
			<NuxtLink to="/"><logo class="w-13 py-6 text-white"></logo></NuxtLink>
			<nav class="hidden laptop:block main-nav">
				<ul class="text-white uppercase flex">
					<li>
						<NuxtLink to="/tjanster/" class="hover:underline">Tjänster</NuxtLink>
					</li>
					<li class="ml-6">
						<NuxtLink to="/kunder/" class="hover:underline">Kunder</NuxtLink>
					</li>
					<!--<li class="ml-6">
						<NuxtLink to="/blogg/" class="hover:underline">Blogg</NuxtLink>
					</li>-->
					<li class="ml-6">
						<NuxtLink to="/om-rove/" class="hover:underline">Om Rove</NuxtLink>
					</li>
					<li class="ml-6">
						<NuxtLink to="/bli-en-rover/" class="hover:underline">Jobb</NuxtLink>
					</li>
				</ul>
			</nav>

			<!-- Hamburger menu icon "$emit('toggle-navigation')" -->
			<div class="block laptop:hidden w-8 h-8 py-2 flex flex-col justify-between" @click="mobileMenuOpen = !mobileMenuOpen">
				<div class="bg-white h-px w-full"></div>
				<div class="bg-white h-px w-full"></div>
				<div class="bg-white h-px w-full"></div>
			</div>

			<!-- Mobile menu -->
			<nav v-if="mobileMenuOpen" class="mobile-nav overflow-y-scroll z-10">
				<div class="wrapper pt-10">
					<ul class="text-white text-24 font-bold uppercase flex flex-col items-center">
						<li>
							<NuxtLink to="/">Startsida</NuxtLink>
						</li>
						<li class="mt-10">
							<NuxtLink to="/tjanster/">Tjänster</NuxtLink>
						</li>
						<li class="mt-10">
							<NuxtLink to="/kunder/">Kunder</NuxtLink>
						</li>
						<!--
						<li class="mt-10">
							<NuxtLink to="/blogg/">Blogg</NuxtLink>
						</li>-->
						<li class="mt-10">
							<NuxtLink to="/om-rove/">Om Rove</NuxtLink>
						</li>
						<li class="mt-10">
							<NuxtLink to="/bli-en-rover/">Jobb</NuxtLink>
						</li>
					</ul>
				</div>
			</nav>
		</div>
	</div>
</template>

<style scoped>
	.main-nav .router-link-exact-active {
		@apply text-pink;
		@apply font-semibold;
	}
</style>

<script setup>
	const mobileMenuOpen = ref(false);
</script>
