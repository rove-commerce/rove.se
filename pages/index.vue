<template>
	<div>
		<cookie-bar />
		<main-navigation @toggle-navigation="toggleNavigation"></main-navigation>
		<footer-navigation></footer-navigation>
		<!--
			<main-navigation @toggle-navigation="toggleNavigation"></main-navigation>
		<jumbotron></jumbotron>
		<blog-summary></blog-summary>
		<contact-form name="startpage-form"></contact-form>
		<testimonials></testimonials>
		<footer-navigation></footer-navigation>-->
	</div>
</template>

<script>
	export default {
		head: {
			title: "E-handel, MarTech och digital marknadsföring | rove.se | Sverige",
			meta: [
				{
					hid: "description",
					name: "description",
					content:
						"Rådgiving B2B digital handel, e-handel, PIM, digital marknadsföring, marketing automation, lead generation, kundresan, upphandling, projektledning | rove.se",
				},
			],
		},

		methods: {
			toggleNavigation() {
				document.body.classList.toggle("nav-open");
			},
		},
	};
</script>
