<template>
	<div>
		<main-navigation @toggle-navigation="toggleNavigation"></main-navigation>

		<!-- Rove Methods -->
		<div class="bg-blue">
			<div class="wrapper py-16">
				<div class="inner-wrapper">
					<div class="w-3/4 laptop:w-2/5 mb-8">
						<img src="/Rove-RGB-Logotyp_Methods-1-Vit.png" />
					</div>
					<div class="text-white text-24 mb-8">
						<p>Rove Methods är utvecklade metoder med tydliga mål och resultat.</p>
					</div>
					<div class="laptop:px-4 py-1 border-t laptop:border-l laptop:border-t-0 border-white mb-12">
						<p class="text-white text-32 mb-4 font-semibold">Kundresan</p>
						<p class="text-white text-16 mb-2">
							Med Rove Kundresan kartlägger vi hur era kunder vill agera under sin kundresa eller köpresa, hur de tar köpbeslut och hur ni bygger
							lojalitet.
						</p>
						<read-link to="/tjanster/kundresan/">Läs mer</read-link>
					</div>
					<div class="laptop:px-4 py-1 border-t laptop:border-l laptop:border-t-0 border-white mb-12">
						<p class="text-white text-32 mb-4 font-semibold">Upphandling</p>
						<p class="text-white text-16 mb-2">
							Med Rove Upphandling leder vi upphandling av system och/eller leverantör av e-handel, PIM eller verktyg för digital marknadsföring
							utifrån vår upphandlingsmetod, från krav till slutlig rekommendation och beslut.
						</p>
						<read-link to="/tjanster/upphandling/">Läs mer</read-link>
					</div>
					<div class="laptop:px-4 py-1 border-t laptop:border-l laptop:border-t-0 border-white">
						<p class="text-white text-32 mb-4 font-semibold">Förstudie</p>
						<p class="text-white text-16 mb-2">
							I Rove Förstudie tar vi fram mål och krav på system och/eller leverantör som ger framgångsrika projekt, med de bästa
							förutsättningarna för att nå era mål och ett lyckat internt införande.
						</p>
					</div>
				</div>
			</div>
		</div>

		<!-- Rove Build -->
		<div class="bg-orange">
			<div class="wrapper py-16">
				<div class="inner-wrapper">
					<div class="w-3/5 laptop:w-2/6 mb-8">
						<img src="/Rove-RGB-Logotyp_Build-Blue.png" />
					</div>
					<div class="text-black text-24 mb-8">
						<p>
							Rove Build är implementationsprojekt för nyutveckling och vidareutveckling enligt vår iterativa projektmodell med fokus smidigt
							införande och låg total ägandekostnad.
						</p>
					</div>
					<div class="laptop:px-4 py-1 border-t laptop:border-l laptop:border-t-0 border-blue mb-12">
						<p class="text-blue text-32 mb-4 font-semibold">Litium e-handel | PIM | CMS</p>
						<p class="text-black text-16 mb-2">
							Vi implementerar er e-handelslösning utifrån era affärsmål - design, systemutveckling, integrationer, utrullning, utbildning, test &
							kvalitetssäkring, interna processer och organisation. Vi arbetar med Litium Commerce Cloud (<nobr>e-handel</nobr>
							, PIM och CMS) och dess paketering Litium Accelerator.
						</p>
					</div>
					<div class="laptop:px-4 py-1 border-t laptop:border-l laptop:border-t-0 border-blue mb-12">
						<p class="text-blue text-32 mb-4 font-semibold">Litium Apps | Add-ons</p>
						<p class="text-black text-16 mb-2">
							Vi utvecklar och förvaltar Apps och Add-ons till Litium Commerce Cloud, exempelvis betallösningar och integrationer till andra
							system.
						</p>
					</div>
					<div class="laptop:px-4 py-1 border-t laptop:border-l laptop:border-t-0 border-blue mb-12">
						<p class="text-blue text-32 mb-4 font-semibold">Headless e-handel</p>
						<p class="text-black text-16 mb-2">
							Implementation av frontend och backend till headless e-handel utifrån era affärsmål - hela vägen från UX-design till API-strategi,
							systemutveckling, integrationer, test & kvalitetssäkring, interna processer till utrullning och produktionssättning.
						</p>
					</div>
					<div class="laptop:px-4 py-1 border-t laptop:border-l laptop:border-t-0 border-blue mb-12">
						<p class="text-blue text-32 mb-4 font-semibold">Headless CMS</p>
						<p class="text-black text-16 mb-2">
							Implementation av headless CMS utifrån er kanalstrategi och marknadsprocess. Vi arbetar bl.a. med Contentful och Storyblok.
						</p>
					</div>
					<div class="laptop:px-4 py-1 border-t laptop:border-l laptop:border-t-0 border-blue mb-12">
						<p class="text-blue text-32 mb-4 font-semibold">Införa HubSpot</p>
						<p class="text-black text-16 mb-2">
							Införande, konfiguration och sätta interna processer för lead generation och digital marknadsföring med HubSpot.
						</p>
					</div>
				</div>
			</div>
		</div>

		<!-- Rove Advisory -->
		<div class="bg-white">
			<div class="wrapper py-16">
				<div class="inner-wrapper">
					<div class="w-3/4 laptop:w-2/5 mb-8">
						<img src="/Rove-RGB-Logotyp_Advisory-1-Bla.png" />
					</div>
					<div class="text-black text-24 mb-8">
						<p>Rove Advisory är rådgivnings- och ledarskapstjänster av erfarna och affärsdrivna ledare och strateger.</p>
					</div>

					<div class="laptop:px-4 py-1 border-t laptop:border-l laptop:border-t-0 border-blue mb-12">
						<p class="text-blue text-32 mb-4 font-semibold">Projektledning</p>
						<p class="text-black text-16 mb-2">
							Med tjänsten Rove Projektledning får ni hjälp med hands-on projektledning från start till mål av en erfaren och affärsdriven
							projektledare.
						</p>
					</div>
					<div class="laptop:px-4 py-1 border-t laptop:border-l laptop:border-t-0 border-blue mb-12">
						<p class="text-blue text-32 mb-4 font-semibold">Styrgruppsarbete</p>
						<p class="text-black text-16 mb-2">
							Med tjänsten Rove Styrgruppsarbete får ni hjälp med deltagande som en neutral part i en styrgrupp för projektet eller att följa upp
							och kvalitetssäkra externa leveranser eller interna processer.
						</p>
					</div>
					<div class="laptop:px-4 py-1 border-t laptop:border-l laptop:border-t-0 border-blue">
						<p class="text-blue text-32 mb-4 font-semibold">Rådgivning</p>
						<p class="text-black text-16 mb-2">Strategisk och hands-on rådgivning för e-handel, PIM och digital marknadsföring.</p>
					</div>
				</div>
			</div>
		</div>

		<!-- Rove Rove Interim Solutions
		<div class="bg-white">
			<div class="wrapper py-16">
				<div class="inner-wrapper">
					<div class="laptop:w-1/2 mb-8">
						<img src="/Rove-RGB-Logotyp_Interim_Solutions-1-Bla.png" />
					</div>
					<div class="text-black text-24 mb-8">
						<p>Rove Interim Solutions är interimslösningar för ledare eller kompletta team som utvecklar och bygger upp er digitala handel.</p>
					</div>

					<div class="laptop:px-4 py-1 border-t laptop:border-l laptop:border-t-0 border-blue mb-12">
						<p class="text-blue text-32 mb-4 font-semibold">E-handelsansvarig</p>
						<p class="text-black text-16 mb-2">
							Med tjänsten Rove E-handelsansvarig leder vi, eller bygger upp, ert e-handelsteam under en kortare eller längre period.
						</p>
					</div>
					<div class="laptop:px-4 py-1 border-t laptop:border-l laptop:border-t-0 border-blue mb-12">
						<p class="text-blue text-32 mb-4 font-semibold">Ansvarig digital markandsföring</p>
						<p class="text-black text-16 mb-2">
							Med tjänsten Rove Ansvarig digital marknadsföring leder vi, eller bygger upp, ert digitala marknadsteam under en kortare eller
							längre period.
						</p>
					</div>
					<div class="laptop:px-4 py-1 border-t laptop:border-l laptop:border-t-0 border-blue">
						<p class="text-blue text-32 mb-4 font-semibold">Komplett team</p>
						<p class="text-black text-16 mb-2">
							Med tjänsten Rove Komplett team kan vi under en period bemanna och bygga upp hela er e-handel eller digitala marknadsfunktion, om
							möjligt mot prestationsbaserad ersättning.
						</p>
					</div>
				</div>
			</div>
		</div> -->

		<!-- Contact Form -->
		<contact-form name="tjanster-form"></contact-form>
		<you-may-also-like></you-may-also-like>
		<footer-navigation></footer-navigation>
	</div>
</template>

<script>
	import MainNavigation from "~/components/MainNavigation";
	import ContactForm from "~/components/ContactForm";
	import FooterNavigation from "~/components/FooterNavigation";
	import PageHeader from "~/components/PageHeader";
	import YouMayAlsoLike from "../../components/YouMayAlsoLike";
	import ReadLink from "../../components/ReadLink";

	export default {
		head: {
			title: "Tjänster | Rove",
			meta: [
				{
					hid: "description",
					name: "description",
					content:
						"Upphandling, projektledning, rådgivning, beslutsunderlag, förstudie, införandestöd, styrgrupp, digital handel, e-handel, PIM, digital marknadsföring, kundresan, köpresan",
				},
			],
		},
		components: {
			MainNavigation,
			ContactForm,
			FooterNavigation,
			PageHeader,
			YouMayAlsoLike,
			ReadLink,
		},

		methods: {
			toggleNavigation() {
				document.body.classList.toggle("nav-open");
			},
		},
	};
</script>
