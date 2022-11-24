<template>
	<div>
		<cookie-bar />
		<main-navigation @toggle-navigation="toggleNavigation"></main-navigation>
		<jumbotron></jumbotron>
		<blog-summary></blog-summary>
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

<script setup>
	useHead({
		title: "E-handel, MarTech och digital marknadsföring | Rove | rove.se | Sverige",
		meta: [
			{
				name: "description",
				content: "Om Rove - e-handel, B2B, PIM, MarTech, digital marknadsföring, marketing automation, lead generation, kundresan, upphandling",
			},
		],
	});

	//const { data } = await useAsyncData("om-rove", () => queryContent("/pages").findOne());

	function toggleNavigation() {
		document.body.classList.toggle("nav-open");
	}
</script>
