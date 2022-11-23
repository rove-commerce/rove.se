<template>
	<div>
		<main-navigation @toggle-navigation="toggleNavigation"></main-navigation>
		<page-header>{{ data.title }}</page-header>
		<div class="bg-white py-20">
			<div class="wrapper">
				<div class="inner-wrapper">
					<div class="wysiwyg" style="max-width: 687px">
						<ContentRenderer :value="data" />
					</div>
				</div>
			</div>
		</div>
		<!--<contact-form name="bli-en-rover-form">Vill du bli en Rover?</contact-form>
		<you-may-also-like></you-may-also-like>-->
		<footer-navigation></footer-navigation>
	</div>
</template>

<script setup>
	useHead({
		title: "Bli en rover | Rove",
		meta: [
			{
				name: "description",
				content: "Bli en Rover - e-handel, PIM, MarTech, digital marknadsföring",
			},
		],
	});

	const { data } = await useAsyncData("om-rove", () => queryContent("/pages/bli-en-rover").findOne());

	function toggleNavigation() {
		document.body.classList.toggle("nav-open");
	}
</script>
