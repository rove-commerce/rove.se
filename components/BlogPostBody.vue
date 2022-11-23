<template>
	<!-- Bild -->
	<!--
        <div class="relative mb-12">
            <picture class="w-full">
                <source media="(max-width: 768px)" srcset="/blogg/placeholder3.jpg">
                <source media="(min-width: 769px)" srcset="/blogg/placeholder2.jpg">
                <img class="w-full" src="/blogg/Johan-1.jpg">
            </picture>
            
            <div class="absolute inset-x-0 bottom-0 white-gradient" style="height: 44%;"></div>
        </div>
        -->
	<div class="wrapper pb-12">
		<div class="inner-wrapper text-center pt-12">
			<!-- Författare -->
			<span class="block text-16 text-black font-bold mb-3"><slot name="author"></slot></span>

			<!-- Datum -->
			<span class="block text-12 text-gray uppercase mb-2"><slot name="date"></slot></span>

			<!-- Rubrik -->
			<h1 class="text-blue text-32 tablet-lg:text-48 leading-tight mb-10"><slot name="title"></slot></h1>
		</div>

		<!-- Body -->
		<div class="laptop:w-10/12 desktop:w-8/12 mx-auto pb-16">
			<div class="wysiwyg">
				<slot name="body"></slot>
			</div>

			<!-- Sociala medier 
                <div class="flex items-center">
                    <icon-facebook-2 style="width: 27px; height: 27px;"></icon-facebook-2>
                    <icon-twitter-2 class="ml-2" style="width: 27px; height: 27px;"></icon-twitter-2>
                    <icon-linked-in-2 class="ml-2" style="width: 27px; height: 27px;"></icon-linked-in-2>
                    <icon-link class="ml-2" style="width: 27px; height: 27px;"></icon-link>
                </div>
                -->
		</div>
	</div>
</template>

<script>
	import IconFacebook2 from "~/components/IconFacebook2";
	import IconTwitter2 from "~/components/IconTwitter2";
	import IconLinkedIn2 from "~/components/IconLinkedIn2";
	import IconLink from "~/components/IconLink";

	export default {
		components: {
			IconFacebook2,
			IconTwitter2,
			IconLinkedIn2,
			IconLink,
		},
		methods: {
			toggleNavigation() {
				document.body.classList.toggle("nav-open");
			},
		},
	};
</script>
