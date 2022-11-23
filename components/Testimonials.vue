<template>
	<div class="bg-blue">
		<div class="wrapper py-20">
			<div class="inner-wrapper flex flex-col laptop:flex-row items-center justify-between">
				<div class="laptop:w-2/5">
					<span class="block text-10 text-white mb-1 uppercase">Överliggare</span>
					<h2 class="text-32 text-white leading-snug mb-3">Vi älskar våra kunder och våra kunder älskar oss</h2>
					<p class="text-white mb-8">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed massa purus.</p>
					<!-- <nuxt-link to="#" class="btn-white hidden laptop:inline-block">Se fler nöjda kunder</nuxt-link> -->
				</div>
				<div class="flex flex-col items-center max-w-md laptop:max-w-none laptop:w-1/2 laptop:pr-6 laptop:pl-8 mx-auto laptop:mx-0">
					<div class="flex items-center bg-white p-8 shadow-pink">
						<div>
							<icon-quote class="w-6 text-red mb-4"></icon-quote>
							<p class="text-blue text-14 mb-2">This product has a bunch of amazing tools which improves our business</p>
							<span class="text-blue text-16 font-bold">Maya Halin</span>
						</div>
						<img src="https://placehold.it/204x204" class="rounded-full ml-2" style="max-width: 102px;" />
					</div>

					<div class="flex items-center bg-white p-8 shadow-yellow mt-5">
						<div>
							<icon-quote class="w-6 text-red mb-4"></icon-quote>
							<p class="text-blue text-14 mb-2">Wow! Using Rove has helped our company constantly improve</p>
							<span class="text-blue text-16 font-bold">Leopold Nilsen</span>
						</div>
						<img src="https://placehold.it/204x204" class="rounded-full ml-2" style="max-width: 102px;" />
					</div>

					<div class="flex items-center bg-white p-8 shadow-green mt-5">
						<div>
							<icon-quote class="w-6 text-red mb-4"></icon-quote>
							<p class="text-blue text-14 mb-2">Rove helped me grow my business by inbound marketing & sales eductation</p>
							<span class="text-blue text-16 font-bold">Felicia Brun</span>
						</div>
						<img src="https://placehold.it/204x204" class="rounded-full ml-2" style="max-width: 102px;" />
					</div>

					<!-- <nuxt-link to="#" class="btn-white inline-block laptop:hidden mt-10">Se fler nöjda kunder</nuxt-link> -->
				</div>
			</div>
		</div>
	</div>
</template>

<script>
	import IconQuote from "~/components/IconQuote";

	export default {
		components: {
			IconQuote,
		},
	};
</script>
