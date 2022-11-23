<template>
	<div>
		<main-navigation @toggle-navigation="toggleNavigation"></main-navigation>
		<services-header>Kundresan</services-header>
		<div class="bg-white py-20">
			<div class="wrapper">
				<div class="inner-wrapper">
					<div class="wysiwyg" style="max-width: 687px;">
						<p class="preamble">
							Med Rove Kundresan kartlägger vi hur era kunder vill agera under sin kundresa eller köpresa, hur de tar köpbeslut och hur ni bygger
							lojalitet.
						</p>
						<p>
							Om ni inte har en tydlig bild av hur kundresan ser ut för att rekrytera nya kunder och affärer är det svårt att lyckas med er
							digitala satsning, ni kommer med stor sannolikhet att missa affärstillfällen.
						</p>
						<p>
							Kundresan börjar inte när kunden når din webbplats eller någon av dina övriga kanaler, den börjar hos kunden innan de har kontakt
							med er, ofta när denne initierar sitt sökande. Kunden kommer välja vilka kanaler denne vill använda, och ni behöver vara följsamma i
							val av kanal och typ av interaktion med kunden.
						</p>
						<p>
							Ni behöver också förstå vem kunden är (målgrupper och personas), hur kunden söker efter information och i vilka steg denne närmar
							sig ett beslut.
						</p>
						<p>För att kartlägga kundresan tar vi fram:</p>
						<ul>
							<li>Målgrupper och Personas (fiktiva personer som representerar en typperson hos en eller flera målgrupper)</li>
							<li>Kundbeteende, hur vill kunden agera genom kundresans olika faser (kanaler, interaktioner, känslor & motivationsfaktorer)</li>
							<li>Kund- och medarbetarintervjuer</li>
							<li>GAP mellan målbild och nuläge</li>
							<li>Unified Commerce: hur får vi det att fungera i praktiken, hur hänger kanalerna ihop?</li>
							<li>Vilka interna processer, organisationer och systemstöd behöver aktiveras i varje steg?</li>
						</ul>
						<p>
							Kartläggning av kundresan görs normalt under 3-4 veckor.
						</p>
						<p>
							Medverkande: representanter för sälj & KAM, marknad, intervjuer med representativa kunder.
						</p>
						<h2>Presentation</h2>

						<!-- Google Slide share -->
						<iframe
							src="https://docs.google.com/presentation/d/e/2PACX-1vRG1hKa9LS-Ha_9AgvOXcFO7kNRHhlTScBEkvM77yqrGfkPOYw2iYnKURVp-YiS89yKF3_WPTYnPoRv/embed?start=false&loop=false&delayms=5000"
							frameborder="0"
							allowfullscreen="true"
							mozallowfullscreen="true"
							webkitallowfullscreen="true"
							class="w-480px h-299px tablet-lg:w-960px tablet-lg:h-569px"
						>
						</iframe>
					</div>
				</div>
			</div>
		</div>
		<contact-form name="tjanster-kundresan-form">Vill du veta mer om Rove Methods Kundresan?</contact-form>
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
			title: "Kundresan | Tjänster | Rove",
			meta: [
				{
					hid: "description",
					name: "description",
					content: "Kartlägga kundresan eller köpresan för e-handel och digital marknadsföring",
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
