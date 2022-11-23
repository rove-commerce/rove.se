<template>
	<nuxt-link v-bind:to="to" class="blog-item flex flex-wrap justify-center -mx-4 pt-8">
		<!-- Om bild finns -->
		<template v-if="imgsrc != ''">
			<!-- Bild -->
			<div class="tablet-lg:w-5/12 desktop:w-4/12 px-4 ml-auto">
				<img class="w-full max-h-full mb-6 tablet-lg:mb-0" v-bind:src="imgsrc" />
			</div>

			<div class="tablet-lg:w-7/12 desktop:w-6/12 px-4 mr-auto flex flex-col">
				<!-- Datum -->
				<span class="block text-12 text-gray uppercase mb-2"><slot name="date"></slot></span>

				<!-- Rubrik -->
				<h2 class="text-blue text-24 laptop:text-32 leading-tight mb-4"><slot name="title"></slot></h2>

				<!-- Summary -->
				<p class="text-black text-16 mb-6"><slot name="summary"></slot></p>

				<!-- Läs länk -->
				<read-link v-bind:to="to"></read-link>
				<!-- <span class="inline-flex items-center text-red underline">Läs <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 15 12" class="ml-2 w-3"><path d="M9.109375.12631579l-1.15625 1.15263158 3.859375 3.9H.078125v1.64210526H11.8125L7.953125 10.7210526l1.15625 1.1526316L14.921875 6z" fill="currentColor" fill-rule="nonzero"></path></svg></span>-->

				<!-- Dela i Sociala -->
				<!--
                    <div class="flex justify-between items-center mt-6 tablet-lg:mt-auto">
                        <span class="block text-12 text-gray">105 visningar</span>
                        <div class="flex items-center">
                            <icon-facebook-2 style="width: 27px; height: 27px;"></icon-facebook-2>
                            <icon-twitter-2 class="ml-2" style="width: 27px; height: 27px;"></icon-twitter-2>
                            <icon-linked-in-2 class="ml-2" style="width: 27px; height: 27px;"></icon-linked-in-2>
                            <icon-link class="ml-2" style="width: 27px; height: 27px;"></icon-link>
                        </div>
                    </div>
                    -->
			</div>
		</template>

		<!-- Om bild saknas -->
		<template v-else>
			<div class="flex flex-col inner-wrapper justify-center px-4 ">
				<!-- Datum -->
				<span class="block text-12 text-gray uppercase mb-2"><slot name="date"></slot></span>

				<!-- Rubrik -->
				<h2 class="text-blue text-24 laptop:text-32 leading-tight mb-4"><slot name="title"></slot></h2>

				<!-- Summary -->
				<p class="text-black text-16 mb-6"><slot name="summary"></slot></p>

				<!-- Läs länk -->
				<read-link v-bind:to="to"></read-link>
			</div>
		</template>
	</nuxt-link>
</template>

<script>
	import ReadLink from "~/components/ReadLink";

	export default {
		components: {
			ReadLink,
		},
		props: {
			to: {
				default: "#",
			},
			imgsrc: {
				default: "",
			},
		},
	};
</script>
