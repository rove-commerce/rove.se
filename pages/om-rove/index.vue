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
		<!--<contact-form name="om-rove-form"></contact-form>
		<you-may-also-like></you-may-also-like>-->
		<footer-navigation></footer-navigation>
	</div>
</template>

<script setup>
	useHead({
		title: "Om Rove | Rove",
		meta: [
			{
				name: "description",
				content: "Om Rove - e-handel, PIM, MarTech, digital marknadsföring ",
			},
		],
	});

	const { data } = await useAsyncData("om-rove", () => queryContent("/pages/om-rove").findOne());
</script>
