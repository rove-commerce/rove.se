<template>
	<div>
		<main-navigation @toggle-navigation="toggleNavigation"></main-navigation>
		<blog-post-body>
			<template v-slot:author>Henrik Lundin</template>
			<template v-slot:title>Få fler leads med en effektiv Content-strategi</template>
			<template v-slot:body>
				<div class="tablet:w-1/2 float-right">
					<img class="ml-4 mb-8" alt="Får ni ut för lite av er Conetent Marketing?" src="/blogg/ContentStrategiCover.png" />
				</div>
				<p class="preamble">Får ni ut för lite av er Content Marketing?</p>
				<p>
					Allt fler företag jobbar med Inbound Marketing och Content Marketing - exempelvis med bloggposter, podcast, webinars, whitepapers, guider,
					filmer - för att öka kännedomen, skapa leads och öka kundnöjdheten.
				</p>
				<p>
					Tyvärr jobbar många på fel sätt och man får inte den effekt man hoppats på. Enligt
					<a
						href="https://www.slideshare.net/mprofs/b2b-content-marketing-2018-benchmarks-budgets-trends-north-america"
						rel="noopener"
						target="_blank"
						>CMI</a
					>
					arbetar mer än 60 % opportunistiskt utan en dokumenterad strategi, vilket resulterar i spridda skurar av content med låg effekt. Man
					stressas att producera mer Content och kanske börjar man tveka på Content Marketing som metod och börjar titta på att gå tillbaka till
					traditionell marknadsföring och försäljning.
				</p>
				<p>
					I den här artikeln går vi igenom hur du lyckas med Content Marketing genom att arbeta med en Content-strategi, ett enkelt och begripligt
					sätt att skapa fokus och större genomslag.
				</p>
				<h3>Osäker på vad Inbound Marketing och Content Marketing innebär?</h3>
				<p>
					Inbound Marketing är ett sätt att arbeta med marknadsföring som innebär att man skapar värde för kunden vilket gör att den blivande kunden
					själv väljer att ta kontakt med er. Man kan säga att man förtjänar kundens intresse. Content Marketing är den vanligaste formen av Inbound
					Marketing där man når sina blivande kunder med relevant innehåll för att skapa intresse och leda kunden vidare i köpresan. Ofta läser den
					blivande kunden först på utan att identifiera sig och väljer sedan att kontakta dig när den är redo. Det betyder att den behöver kunna ta
					sig vidare en bra bit i köpresan helt på egen hand, <strong>kontakt med er sker först när ni redan är med på kort-listan</strong>.
				</p>
				<p>
					Motsatsen till Inbound Marketing heter Outbound Marketing där det säljande företaget istället hör av sig till prospects, exempelvis genom
					annonser, telemarketing eller reklam. Problemet med Outbound är att köpare idag ofta upplever den här typen av marknadsföring som
					påträngande och avbrytande.
				</p>
				<h3>Vad är en Content-Strategi?</h3>
				<div class="mb-2 text-18">En Content-Strategi beskriver:</div>
				<ol>
					<li>vad man vill prata om,</li>
					<li>till vem och</li>
					<li>i vilken fas i kundresan.</li>
				</ol>
				<div class="mb-2 text-18">Syftet är att:</div>
				<ul>
					<li>
						identifiera vilket <strong>innehåll som skapar värde</strong> för kunden i olika delar av kundresan (och som för kunden framåt i
						säljtratten)
					</li>
					<li>få ett <strong>fokus i kommunikationen</strong>, att upprepa ett fåtal budskap istället för spridda skurar</li>
					<li>mappa <strong>rätt innehåll mot rätt målgrupp och persona</strong></li>
					<li>skapa möjligheter för <strong>utvärdering, analys och förbättring</strong></li>
				</ul>
				<p>
					En Content-strategi är inte en redaktionell plan eller en detaljerad beskrivning av vilka kanaler som ska användas. Det är nästa
					planeringsnivå.
				</p>
				<h3>Kundresor, Teman, Målgrupper och Personas</h3>
				<p>
					Ett enkelt sätt att komma igång är att arbeta med kommunikativa teman - vad är det vi vill prata om med våra kunder? Teman ger ett tydligt
					fokus och hjälper er att säkerställa att innehållet inte spretar för mycket. Att upprepa samma budskap är viktigt.
				</p>
				<p>
					Ett tema är inte lika med ett Content, teman beskriver vad ni vill prata om. Ett tema innehåller flera olika Content, exempelvis en
					bloggpost, en guide, en film och ett antal bloggposter i sociala media som sprider dessa. Ibland är teman ännu större, de kan innehålla
					flera kampanjer som i sin tur innehåller flera Content.
				</p>
				<div class="mb-2 text-18">
					Att arbeta fokuserat med teman kommer att ge en positiv effekt, men den verkliga magin ligger i att mappa ut sina teman i kundresans olika
					faser mot era olika målgrupper. Om ni inte har gjort ett arbete med att
					<nuxt-link to="/tjanster/kundresan/">kartlägga era kundresor</nuxt-link> kan ni gott använda grundmallen för en kundresa:
				</div>
				<div>
					<table class="border border-collapse mb-2">
						<tr class="border">
							<th class="p-2 border text-left">Fas</th>
							<th class="p-2 border text-left">Beskrivning</th>
						</tr>
						<tr class="border">
							<td class="p-2 border">Awareness</td>
							<td class="p-2 border">Kunden förstår att de har en möjlighet, behov eller utmaning.</td>
						</tr>
						<tr class="border">
							<td class="p-2 border">Consideration</td>
							<td class="p-2 border">Kunden definierar sin utmaning, efterforskar och jämför de olika lösningarna.</td>
						</tr>
						<tr class="border">
							<td class="p-2 border">Decision</td>
							<td class="p-2 border">Kunden är redo att köpa och väljer en lösning, köpbeslut!</td>
						</tr>
						<tr class="border">
							<td class="p-2 border">Loyalty</td>
							<td class="p-2 border">
								Upplevelsen efter kundens köp. Fokus på att göra kunden till en återkommande kund, service, kundtjänst, kommunikation.
							</td>
						</tr>
						<tr class="border">
							<td class="p-2 border">Ambassador</td>
							<td class="p-2 border">Kunden blir er ambassadör och rekommenderar er till andra.</td>
						</tr>
					</table>
				</div>
				<p>
					Om ni vill börja med köpresan snarare än hela kundresan hoppar ni över faserna Loyalty och Ambassador. Och tänk på att inte arbeta med för
					många teman mot samma målgrupp och kundresefas samtidigt.
				</p>
				<p>
					När man börjar ta fram teman för olika delar av kundresan behöver man också titta på vilka målgrupper eller personas de riktar sig till.
					Vanligtvis har de olika målgrupperna/personas olika utmaningar och drivkrafter som ibland medför att olika teman passar bättre eller sämre.
					Olika personas kommer också in på olika ställen i kundresan. Det man ska ta fasta på är att
					<strong>det ska finnas teman för varje målgrupp/aktuell persona i varje fas av kundresan</strong>.
				</p>
				<div class="mb-2 text-18">Så här skulle det kunna se ut för ett företag som säljer videokonferensutrustning B2B med målgrupperna:</div>
				<ul>
					<li>Offentlig sektor</li>
					<li>Tech-bolag</li>
				</ul>
				<div class="mb-2 text-18">med följande personas:</div>
				<ul>
					<li>CIO (Tech-bolag)</li>
					<li>Inköpsansvarig (Offentlig sektor)</li>
					<li>Medarbetare (Offentlig sektor och Tech-bolag)</li>
				</ul>
				<h4>Awareness</h4>
				<p>
					Idé: vi vill nå företag som har börjat fundera på hur de ska arbeta under och efter Covid-19 samt hur man jobbar distribuerat i flera
					länder. De har ett problem och ett behov, men de har inte börjat titta på konkreta lösningar ännu.
				</p>
				<p>
					Värde: ge kunden uppslag på hur andra har gjort, presentera trender och statistik som ger interna argument för att titta vidare på
					utrustning för distansarbete.
				</p>
				<div class="mb-2 text-18">Teman:</div>
				<ul>
					<li>Att arbeta hemma är lika effektivt som att arbeta på kontor (alla personas)</li>
					<li>Jobba effektivt i utspridda team (alla personas)</li>
					<li>Därför kommer man inte gå tillbaka till stora lokaler efter Covid-19 (inköpsansvarig och CIO)</li>
					<li>Säkerhet vid hemmaarbete (CIO)</li>
				</ul>
				<h4>Consideration</h4>
				<p>
					Idé: vi vill nå de som letar efter videokonferensutrustning som lösning på problemet. Vi vill förklara varför det är vettigt att titta på de
					lite mer kvalificerade (och dyrare) lösningarna istället för den billigaste utrustningen som man kanske tänker på först. Vi vill också skapa
					ett sug underifrån, att anställda ska efterfråga bra utrustning.
				</p>
				<p>Värde: berätta att den typ av utrustning vi säljer ger lägre kostnader i längden, besparar användaren strul och avlastar IT-avdelningen.</p>
				<div class="mb-2 text-18">Teman:</div>
				<ul>
					<li>Den här utrustningen behövs för att kunna jobba hemma (alla personas)</li>
					<li>Att tänka på när du ska välja konferensutrustning (CIO och inköpsansvarig)</li>
					<li>Så automatiserar du installation av utrustning för distansmöten (CIO)</li>
				</ul>
				<h4>Decision</h4>
				<p>Idé: nu vill vi få ett köpbeslut. Kunden jämför vår lösning med några andra konkurrenter.</p>
				<p>
					Värde: tydligt visa upp de värden vår utrustning ger, rik produktinformation, lätt att ta kontakt och få svar på frågor samt presentera
					relevanta kundcase.
				</p>
				<div class="mb-2 text-18">Teman:</div>
				<ul>
					<li>Helautomatiserad lösning ger lägre TCO (CIO och inköpsansvarig)</li>
					<li>Säkerhet (CIO)</li>
					<li>Helt utan krångel för användarna (alla personas)</li>
					<li>Kundvittnesmål (CIO och inköpsansvarig)</li>
					<li>Nöjd-kund-garanti (CIO och inköpsansvarig)</li>
				</ul>
				<h4>Loyalty</h4>
				<p>Idé: kunden har köpt vår utrustning, nu vill vi att den ska känna sig riktigt nöjd och köpa mer.</p>
				<p>Värde: ge kunden tips på hur man får ut det mesta av våra produkter, besvara frågor, berätta om hur andra har gjort.</p>
				<div class="mb-2 text-18">Teman:</div>
				<ul>
					<li>Få ut mer av produkterna (alla personas)</li>
					<li>Vanliga frågor & svar (alla personas)</li>
					<li>Så gör andra kunder (CIO och inköpsansvarig)</li>
				</ul>
				<h4>Ambassador</h4>
				<p>Idé: kunden är riktigt nöjd, nu vill förmå den att agera ambassadör och berätta för andra.</p>
				<p>
					Värde: förklara hur kunden kan bli bättre på employer branding genom att utnyttja sociala media för att marknadsföra sig som en bra
					arbetsplats.
				</p>
				<div class="mb-2 text-18">Teman:</div>
				<ul>
					<li>Employer branding - Våra medarbetare har en fantastiskt arbetsplats hemma (Medarbetare och CIO)</li>
					<li>Employer branding - en toppmodern global arbetsplats (Medarbetare och CIO)</li>
				</ul>
				<p>Voilá, där har du en enkel men kraftfull Content-strategi! Sammanfatta på en A4 per målgrupp och sätt upp på väggen. Exempel:</p>
				<p>
					<a href="/blogg/Exempel Content-strategi.pdf" target="_blank">
						<img class="ml-4 mb-8" alt="Exempel Content-strategi för Content Marketing" src="/blogg/ContentStrategiExempel.png" />
						<p>Ladda ner exempel-sammanställningen här.</p>
					</a>
				</p>
				<p>I nästa bloggpost fortsätter vi med hur du använder Content-strategin i din praktiska planering och kopplar på Marketing Automation.</p>
				<p>
					Behöver du hjälp med din Content-strategi eller Content Marketing? Det finns flera svenska byråer som kan hjälpa dig vidare, titta
					exempelvis på duktiga <a class="font-blue" rel="noopener" href="https://crescando.se/" target="_blank">Crescando</a>.
				</p>
			</template>
		</blog-post-body>
		<footer-navigation></footer-navigation>
	</div>
</template>

<script>
	import MainNavigation from "~/components/MainNavigation";
	import FooterNavigation from "~/components/FooterNavigation";
	import BlogPostBody from "~/components/BlogPostBody";

	export default {
		head: {
			title: "Blogg | Få fler leads med en effektiv Content-strategi | Rove",
			meta: [
				{
					hid: "description",
					name: "description",
					content:
						"Får ni ut för lite av er Content Marketing? I den här artikeln går vi igenom hur du lyckas med Content Marketing genom att arbeta med en Content-strategi, ett enkelt och begripligt sätt att skapa fokus och större genomslag.",
				},
			],
		},
		components: {
			MainNavigation,
			FooterNavigation,
			BlogPostBody,
		},

		methods: {
			toggleNavigation() {
				document.body.classList.toggle("nav-open");
			},
		},
	};
</script>
