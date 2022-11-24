<template>
	<div>
		<main-navigation @toggle-navigation="toggleNavigation"></main-navigation>
		<page-header>Blogg</page-header>

		<div class="wrapper py-16">
			<!-- Sök
        <div class="inner-wrapper flex justify-end">
            <div class="bg-gray-light text-blue text-12 flex items-center border-b border-blue">
                <input class="bg-transparent w-32 py-2 px-3 leading-none appearance-none focus:outline-none" type="text" placeholder="Sök">
                <button class="py-2 px-3 cursor-pointer appearance-none focus:outline-none">
                    <icon-search class="w-3 h-3"></icon-search>
                </button>
            </div>
        </div>
        -->

			<!-- PunchOut -->
			<blog-list-item to="/blogg/punchout/" imgsrc="/blogg/punchout-ehandel.jpg">
				<template v-slot:date> 1 December 2020 </template>
				<template v-slot:title> PunchOut e-handel - öppna en ny försäljningskanal till era kunder </template>
				<template v-slot:summary>
					Vad är PunchOut e-handel? PunchOut är en försäljningskanal där era kunder kan köpa från er e-handel direkt från sina inköpssystem.
				</template>
			</blog-list-item>

			<!-- Upphandla e-handelsprojekt -->
			<blog-list-item to="/blogg/upphandla-ehandelsprojekt/" imgsrc="/blogg/upphandla ehandelsprojekt.jpg">
				<template v-slot:date> 27 November 2020 </template>
				<template v-slot:title> Upphandla e-handelsprojekt </template>
				<template v-slot:summary>
					Ska du upphandla ett e-handelsprojekt? I den här artikeln går vi igenom problem-topplistan och hur du bör göra istället.
				</template>
			</blog-list-item>

			<!-- Få fler leads med en effektiv Content-strategi -->
			<blog-list-item to="/blogg/content-strategi/" imgsrc="/blogg/Content Strategi cover.png">
				<template v-slot:date> 19 November 2020 </template>
				<template v-slot:title> Få fler leads med en effektiv Content-strategi </template>
				<template v-slot:summary> Får ni ut för lite av er Content Marketing? </template>
			</blog-list-item>

			<!-- Vilken organisation behövs för en B2B e-handel? Del 2. -->
			<blog-list-item to="/blogg/organisation-ehandel-b2b-2/" imgsrc="/blogg/Bild-1-org-e-handel-b2b.png">
				<template v-slot:date> 3 Augusti 2020 </template>
				<template v-slot:title> Vilken organisation behövs för en B2B e-handel? Del 2. </template>
				<template v-slot:summary>
					I den här bloggserien tittar vi på hur man bör organisera sig och vilka processer som behövs för en framgångsrik B2B e-handel. I del 1 gick
					vi igenom de olika processer som man behöver och vad de innebär. Nu går vi vidare och konkretiserar vem som gör vad genom att titta på 3
					exempelorganisationer.
				</template>
			</blog-list-item>

			<!-- Sökmotormarknadsföring för B2B med 6 tips för bättre annonsering -->
			<blog-list-item to="/blogg/sem-b2b/" imgsrc="/blogg/Johan-1.jpg">
				<template v-slot:date> 19 Juni 2020 </template>
				<template v-slot:title> Sökmotormarknadsföring för B2B med 6 tips för bättre annonsering </template>
				<template v-slot:summary>
					Sökmotorannonsering är en av de kanaler som ger mest ”bang for the buck”. I det här inlägget berättar jag mer om SEM och ger sex tips.
				</template>
			</blog-list-item>

			<!-- Sälja direkt och kanalkonflikter -->
			<blog-list-item to="/blogg/kanalkonflikter/" imgsrc="/blogg/AndréBusiness.jpg">
				<template v-slot:date> 16 Juni 2020 </template>
				<template v-slot:title> Sälja direkt och kanalkonflikter </template>
				<template v-slot:summary>
					Kanalkonflikter är ett av de vanligaste skälen till att B2B-företag tvekar med att börja med e-handel. Man är orolig för hur
					återförsäljarledet kommer att reagera. Å andra sidan finns stora fördelar med att ha större kontroll, snabbhet och insikt i hela
					försäljningsprocessen, både för tillverkaren och för slutkunden.
				</template>
			</blog-list-item>

			<!-- Vilken organisation behövs för att driva en B2B e-handel? Del 1. -->
			<blog-list-item to="/blogg/organisation-ehandel-b2b/">
				<template v-slot:date> 13 Maj 2020 </template>
				<template v-slot:title> Vilken organisation behövs för att driva en B2B e-handel? Del 1. </template>
				<template v-slot:summary>
					I den här bloggserien tittar vi på hur man bör organisera sig och vilka processer som behövs för en framgångsrik B2B e-handel.
				</template>
			</blog-list-item>

			<!-- Ordlista för e-handel B2B -->
			<blog-list-item to="/blogg/ordlista-ehandel-b2b/">
				<template v-slot:date> 15 April 2020 </template>
				<template v-slot:title> Ordlista för e-handel B2B </template>
				<template v-slot:summary>
					Nu kör vi igång med vår e-handelsskola B2B e-handel för nybörjare! Innan vi hoppar in och börjar prata om hur vi attraherar, konverterar och
					får lojala kunder ska vi börja med att förklara viktiga begrepp och termer, en ordlista för B2B e-handel.
				</template>
			</blog-list-item>

			<!-- Trender, tips och fallgropar för digital handel B2B -->
			<blog-list-item to="/blogg/trender-tips-och-fallgropar-digital-handel-b2b/">
				<template v-slot:date> 20 Mars 2020 </template>
				<template v-slot:title> Trender, tips och fallgropar för digital handel B2B </template>
				<template v-slot:summary>
					Webinar från den 10 mars 2020. E-handelsplattformen Litium bjöd in mig för att hålla ett Webinar om trender, erfarenheter och vanliga
					misstag för digital B2B-handel. Härligt, mitt favoritämne alla kategorier.
				</template>
			</blog-list-item>

			<!-- Paging -->
			<!--
        <div class="inner-wrapper flex items-center justify-between pt-10">
            <span class="block text-16 text-black">Sida 1 av 10</span>
            <div class="flex text-16 text-blue">
                <nuxt-link to=#" class="border border-blue-light rounded-md flex items-center px-4" href="#"><icon-chevron-left style="width: 6px;"></icon-chevron-left></nuxt-link>
                <div class="bg-blue-light mx-2 font-medium p-2 rounded-md text-center" style="min-width: 100px;">1</div>
                <nuxt-link to=#" class="border border-blue-light rounded-md flex items-center px-4" href="#"><icon-chevron-right style="width: 6px;"></icon-chevron-right></nuxt-link>
            </div>
        </div>
        --></div>
		<footer-navigation></footer-navigation>
	</div>
</template>

<script>
	import MainNavigation from "~/components/MainNavigation";
	import FooterNavigation from "~/components/FooterNavigation";
	import PageHeader from "~/components/PageHeader";
	import IconFacebook2 from "~/components/IconFacebook2";
	import IconTwitter2 from "~/components/IconTwitter2";
	import IconLinkedIn2 from "~/components/IconLinkedIn2";
	import IconLink from "~/components/IconLink";
	import IconSearch from "~/components/IconSearch";
	import IconChevronLeft from "~/components/IconChevronLeft";
	import IconChevronRight from "~/components/IconChevronRight";
	import BlogListItem from "~/components/BlogListItem";

	export default {
		head: {
			title: "Blogg | Rove",
			meta: [
				{
					hid: "description",
					name: "description",
					content: "Blogg - e-handel, digital marknadsföring, PIM",
				},
			],
		},
		components: {
			MainNavigation,
			FooterNavigation,
			PageHeader,
			IconFacebook2,
			IconTwitter2,
			IconLinkedIn2,
			IconLink,
			IconSearch,
			IconChevronLeft,
			IconChevronRight,
			BlogListItem,
		},

		methods: {
			toggleNavigation() {
				document.body.classList.toggle("nav-open");
			},
		},
	};
</script>
