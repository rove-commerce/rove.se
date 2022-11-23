<template>
	<div class="bg-white py-20">
		<div class="wrapper">
			<div class="inner-wrapper">
				<div class="wysiwyg" style="max-width: 687px;">
					<p class="preamble">
						Vi vill bygga ett framgångsrikt och riktigt bra företag, med stark kultur och stort kundfokus. Vi ska vara ett värderingsdrivet
						kunskapsföretag som arbetar i frontlinjen inom digital handel. Vi ska arbeta med innovativa affärsmodeller och utvecklade metoder
						baserade på ny kunskap, erfarenhet, omvärldsbevakning och input från de bästa i branschen. Allt i syfte att göra våra kunder
						framgångsrika genom digital handel. Vår vision är att bli Sveriges ledande kunskapsföretag inom digital handel för B2B.
					</p>
					<p>
						Vilka hårda och mjuka fördelar finns, vad är ROI? Vilken kostnadsnivå talar vi om? Med Business Case tar vi tillsammans under några
						veckor och två eller tre sessioner fram ett beslutsunderlag inklusive ROI-kalkyl och intäkts- och kostnadsestimeringar.
					</p>
					<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam lobortis iaculis nisi quieuismod. Aenean tincidunt tempus scelerisque.</p>

					<ul>
						<li>Phasellus rhoncus mauris ex, in mollis eros scelerisque id.</li>
						<li>Praesent egestas, erat a vestibulum lobortis, enim mi condimentum lacus, a vestibulum massa purus a lacus.</li>
						<li>In condimentum nunc magna, et commodo dolor placerat vehicula.</li>
						<li>Aliquam interdum ligula lectus, vel vehicula nibh fermentum eget.</li>
						<li>Morbi sed mollis leo. Ut tortor urna, blandit efficitur tempus sagittis, ultrices eget purus.</li>
					</ul>

					<p>Business case finns i tre varianter:</p>

					<div class="border-t border-blue-transparent mb-12">
						<expandable-text></expandable-text>
						<expandable-text></expandable-text>
						<expandable-text></expandable-text>
						<expandable-text></expandable-text>
					</div>
				</div>

				<div class="w-full text-center tablet:text-left">
					<nuxt-link to="#" class="btn-blue inline-block mb-20">Kontakta oss</nuxt-link>
				</div>

				<!-- google slides placeholder -->
				<div class="w-full mb-24">
					<img src="https://placehold.it/686x410/0532D1/FFFFFF?text=Google%20Slides%20placeholder" />
				</div>
			</div>
		</div>
	</div>
</template>

<script>
	import IconChevronDown from "~/components/IconChevronDown";
	import IconChevronUp from "~/components/IconChevronUp";
	import IconArrowRight from "~/components/IconArrowRight";
	import ExpandableText from "~/components/ExpandableText";

	export default {
		components: {
			IconChevronDown,
			IconChevronUp,
			IconArrowRight,
			ExpandableText,
		},
	};
</script>
