<template>
	<div class="bg-white py-12 border-t border-blue-light">
		<div class="wrapper flex flex-col tablet-lg:flex-row justify-between items-center">
			<nuxt-link to="/"><logo class="text-blue w-12" symbols-color="#FFD5CF"></logo></nuxt-link>
			<div class="flex mt-6 tablet-lg:mt-0 items-center">
				<!-- Twitter
                    <a rel="noopener" href="#">
                    <icon-twitter class="text-blue w-10"></icon-twitter>
                </a>
                -->
				<span class="text-blue text-12">Följ oss på</span>
				<a href="https://www.linkedin.com/company/rove" rel="noopener" target="_blank">
					<icon-linked-in class="text-blue w-10"></icon-linked-in>
				</a>
				<!-- Facebook
                <a href="#" rel="noopener" class="ml-5">
                    <icon-facebook class="text-blue w-10"></icon-facebook>
                </a>
                -->
			</div>
			<div class="text-blue text-12 mt-6 tablet-lg:mt-0">
				<a href="https://www.litium.se" rel="noopener" target="_blank">
					<img class="w-24" alt="Litium Partner" src="/litium2020-Logo-RGB_Black.png" />
				</a>
			</div>
			<div class="text-blue text-12 mt-6 tablet-lg:mt-0">
				<img class="h-24" alt="Hubspot Solution Provider" src="/partner-badge-color.png" />
			</div>
			<div class="text-blue text-12 mt-6 tablet-lg:mt-0">
				<nuxt-link to="/privacy/" class="ml-4 hover:underline">Cookies & Integritetspolicy</nuxt-link>
			</div>
			<div class="text-blue text-12 mt-6 tablet-lg:mt-0">
				<span>© 2022 Rove Commerce Advisory AB</span>
			</div>
		</div>
	</div>
</template>
