<template>
	<div>
		<main-navigation @toggle-navigation="toggleNavigation"></main-navigation>
		<services-header>Upphandling</services-header>
		<div class="bg-white py-20">
			<div class="wrapper">
				<div class="inner-wrapper">
					<div class="wysiwyg" style="max-width: 687px;">
						<p class="preamble">
							Med Rove Upphandling leder vi upphandling av system och/eller leverantör av e-handel, PIM eller verktyg för digital marknadsföring
							utifrån vår upphandlingsmetod, från krav till slutlig rekommendation och beslut.
						</p>
						<p>Metoden innefattar:</p>
						<ul>
							<li>en översiktlig omvärldsanalys,</li>
							<li>affärsmål,</li>
							<li>ta fram kravunderlag (eventuellt inkl legala krav),</li>
							<li>RFP/RFI-dokument,</li>
							<li>utvärderingskriterier och</li>
							<li>organisatoriska förutsättningar.</li>
						</ul>

						<h2>Presentation</h2>
						<iframe
							src="https://docs.google.com/presentation/d/e/2PACX-1vSmYHdVXEcaex8OMIfhNuXztkhW5eSBicnGJwA8saUav_Z-zXVMJBZIDba1XW4chEjJVdGFmbn4x2dm/embed?start=false&loop=false&delayms=3000"
							frameborder="0"
							width="480"
							height="299"
							allowfullscreen="true"
							mozallowfullscreen="true"
							webkitallowfullscreen="true"
							class="w-480px h-299px tablet-lg:w-960px tablet-lg:h-569px"
						></iframe>
					</div>
				</div>
			</div>
		</div>
		<contact-form name="tjanster-upphandling-form">Vill du veta mer om Rove Methods Upphandling?</contact-form>
		<you-may-also-like></you-may-also-like>
		<footer-navigation></footer-navigation>
	</div>
</template>

<script>
	import MainNavigation from "~/components/MainNavigation";
	import ContactForm from "~/components/ContactForm";
	import FooterNavigation from "~/components/FooterNavigation";
	import ServicesHeader from "~/components/ServicesHeader.vue";
	import YouMayAlsoLike from "../../components/YouMayAlsoLike.vue";

	export default {
		head: {
			title: "Upphandling | Tjänster | Rove",
			meta: [
				{
					hid: "description",
					name: "description",
					content: "Leda upphandling av system och leverantör av e-handel, PIM, digital marknadsföring",
				},
			],
		},
		components: {
			MainNavigation,
			ContactForm,
			FooterNavigation,
			ServicesHeader,
			YouMayAlsoLike,
		},

		methods: {
			toggleNavigation() {
				document.body.classList.toggle("nav-open");
			},
		},
	};
</script>
