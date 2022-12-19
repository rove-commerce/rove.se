<template>
	<div>
		<main-navigation @toggle-navigation="toggleNavigation"></main-navigation>
		<page-header>Tack!</page-header>
		<div class="wrapper">
			<div class="inner-wrapper mt-8">
				<p>Tack för ditt svar, vi tittar på det så snart vi har möjlighet!</p>
			</div>
		</div>
		<you-may-also-like></you-may-also-like>
		<footer-navigation></footer-navigation>
	</div>
</template>

<script>
	import MainNavigation from "~/components/MainNavigation";
	import FooterNavigation from "~/components/FooterNavigation";
	import PageHeader from "~/components/PageHeader";
	import YouMayAlsoLike from "../../components/YouMayAlsoLike.vue";

	export default {
		components: {
			MainNavigation,
			FooterNavigation,
			PageHeader,
			YouMayAlsoLike,
		},

		methods: {
			toggleNavigation() {
				document.body.classList.toggle("nav-open");
			},
		},
	};
</script>
