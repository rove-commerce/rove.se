<template>
	<div>
		<main-navigation @toggle-navigation="toggleNavigation"></main-navigation>
		<blog-post-body>
			<template v-slot:author> Johan Åström </template>
			<template v-slot:date> 19 Juni 2020 </template>
			<template v-slot:title>
				Sökmotormarknadsföring för B2B med 6 tips för bättre annonsering
			</template>
			<template v-slot:body>
				<div class="tablet:w-1/2 float-right">
					<img class="ml-4 mb-8" src="/blogg/Johan Åström2.png" />
				</div>
				<p>
					Marknadsavdelningens ständiga utmaning är att investera budgeten där den får bäst effekt. Sökmotorannonsering är en av de kanaler som ger
					mest “bang for the buck” enligt en undersökning från
					<a href="https://www.disruptiveadvertising.com/adwords/grow-b2b-business/" rel="noopener" target="_blank">Disruptive Advertising</a>.
					Kanalen träffar rätt mot målgruppen och är svår att matcha vad gäller pris och flexibilitet.
				</p>
				<p>
					Jag heter Johan Åström och jobbar som SEM-specialist på
					<a href="https://searchintent.se/" rel="noopener" target="_blank">SearchIntent</a>. I det här inlägget berättar jag mer om SEM,
					sökmotormarknadsföring, och ger sex tips på hur du kan förbättra din annonsering.
				</p>

				<h3>Vad är annonsering i sökmotorer?</h3>
				<p>
					SEM står för Search Engine Marketing och är den vanligaste benämningen på betald annonsering i sökmotorer som Google, Bing och Yahoo. Ibland
					används också begreppen SEA (Search Engine Advertising) och PPC (Pay per click). Med sökmotorer får du chansen att exponeras på den kanal
					där majoriteten börjar sin kundresa, då hela
					<a href="https://www.fronetics.com/10-stats-know-b2b-buyers-journey/" rel="noopener" target="_blank">62% av B2B-köpare</a>
					börjar med att använda sig av sökmotorer inför ett köp.
				</p>
				<div class="tablet:w-3/4 mb-4">
					<img src="/blogg/google ads.png" />
				</div>
				<p>
					<i
						>Annonseringen går ut på att nå ut till kunder genom att köpa annonser i sökmotorer baserat på utvalda sökord och målgrupper. Det vi ser
						under annonserna är det organiska resultatet som kallas för SEO (Search Engine Optimization) och är något jag kommer prata om i ett
						senare inlägg.</i
					>
				</p>

				<h3>Varför sökmotorannonsering och vad kommer det att kosta?</h3>
				<p>
					Med marknadsföring generellt är det viktigt med relevans. Du vill inte skjuta för brett, det resulterar i att du betalar för personer som
					inte är en del av målgruppen. Sökmotorannonsering kan med stor träffsäkerhet riktas till en specifik målgrupp och du betalar bara när någon
					klickar på annonsen. Sker det inga klick är annonseringen ett helt gratis skyltfönster.
				</p>
				<p>
					Rent praktiskt budar du på ett sökord som sedan kommer leda till kostnaden per klick. Du kommer inte att behöver betala mer än ditt bud,
					däremot kan du få billigare klickkostnader om sökmotorn anser att du förtjänar det. De bättre priserna baseras på relevansen mellan
					sökordet, budgivningen, annonsonstexten och landningssidan. Detta för att sedan värdera om annonseringen matchar sökningens avsikt, även
					kallat sökintention. Sökmotorerna belönar helt enkelt relevans och mitt tips är att lägga fokus på att hitta rätt sökord till landningssidan
					för att säkerställa det bästa priset. Relevansen i sökmotorerna är så pass viktig att det har blivit en av grundstenarna för en framgångsrik
					annonsering.
				</p>

				<h3>Räkneexempel</h3>
				<p>
					Låt oss säga att du ska investera 100 000 kr i sökmotorannonsering för tjänstebilar. En kund söker på Google efter “volvo tjänstebil”, ett
					sökord som du budar 4 kr för.
				</p>
				<p>
					En investering på 100 000 kr och ett pris per klick på 4 kr ger dig 25 000 besökare. CVR (konverteringsgraden) för B2B är i snitt
					<a href="https://www.wordstream.com/blog/ws/2016/02/29/google-adwords-industry-benchmarks" rel="noopener" target="_blank">3,04%</a>. Det
					innebär att du skulle få 760 konverteringar och ett snittpris på 132 kr per konvertering.
				</p>
				<p>
					Om ett avtal för en tjänstebil är värt 2 000 kr, genererar 760 konverteringar 1 520 000 kr. Det innebär att du som mest kan betala 1 999 kr
					i snitt per konvertering och fortfarande driva en lönsam annonsering. För att genomföra en vinstdrivande marknadsföring måste du därför veta
					vad du har råd att betala för en konvertering..
				</p>

				<h3>Hur optimerar du på bästa sätt?</h3>
				<p>
					En stor fördel med digital marknadsföring är att det går att mäta, med hjälp av exempelvis
					<strong>Google Tag Manager</strong> kan du “spåra” händelser som <strong>klick på kontakt</strong> eller
					<strong>inskickade formulär</strong>. Spårningen gör att du kan se exakt vad investeringen genererar samt se vilka sökord som konverterar.
					Tack vare detta kan du optimera efter konverteringar och ständigt förbättra vinsten i marknadsföringen. Utan spårningen annonserar du med
					ögonbindel och har ingen aning om när du prickar rätt. Allt av värde bör därför spåras och mätas för att sedan stå till grund för
					optimeringen.
				</p>

				<h3>Vilken sökmotor ska du välja?</h3>
				<p>
					Den överlägset största kanalen för SEM är Google med sitt verktyg
					<a href="https://searchintent.se/tjanster/google-ads/" rel="noopener" target="_blank">Google Ads</a>. Anledningen är att Google står för 96
					% av sökmarknaden - så vill man annonsera på den plattform där kunderna finns är Googles sökmotor det självklara valet.
				</p>

				<h3>Du får värdefull information om konkurrenterna</h3>
				<p>
					En annan fördel med Google Ads är
					<strong>auktionsinformationen</strong>, där får du information om vilka annonskonton som budar på samma sökord som du och hur stor synlighet
					de har. Detta ger dig värdefull kunskap om din egen samt konkurrenternas synlighet på Google. Ett annonskonto döps efter verksamhet
					alternativ domän, vilket gör att du ska se exakt vilka konkurrenter som annonserar under samma segment. Du får alltså en översikt där du kan
					finna inspiration och insikter om hur du ska ta marknadsandelar och vinna fler kunder.
				</p>

				<h3>6 sätt att förbättra din annonsering på Google</h3>

				<p>
					En del jobbar redan med Google Ads men är missnöjda med prestationen. Ofta beror det på något av följande:
				</p>

				<ol>
					<li>
						<strong>Felaktiga sökordstyper</strong><br />Det finns olika sökordstyper som berättar för sökmotorerna hur brett de ska tolka sökorden.
						Sökord med bred tolkning gör att dina annonser syns på liknande söktermer, vilket kan leda till att du betalar för att synas på
						sökningar som inte genererar konverteringar. Detta behöver dock inte vara fel, att synas på liknande termer kan vara ett bra sätt att
						hitta nya sökord. Jag skulle rekommendera dig att gå igenom söktermerna som plockats upp och lägga till s.k. “negativa sökord”. Negativa
						sökord innebär att utesluter söktermer och bara fokusera på de sökord som genererar relevant trafik, på så vis säkerställer du relevanta
						besökare.
					</li>
					<li>
						<strong>Felaktig spårning</strong><br />Om spårningen är fel kommer det leda till felaktiga rapporter som leder till felaktiga beslut.
					</li>
					<li>
						<strong>Dåliga annonstexter</strong><br />Det är viktigt att annonserna är så nära sökordet som möjligt och är skrivna så att de sticker
						ut och “vinner klicket”.
					</li>
					<li>
						<strong>Platsinriktning är inte korrekt uppsatt</strong><br />Om potentiella kunder befinner sig på en specifik geografisk plats är det
						viktigt att styra annonserna dit.
					</li>
					<li>
						<strong>Felaktig budgivning i förhållande till datum och tid</strong><br />För många företag finns det ingen vinning i att annonsera
						alla dagar, dygnet runt. Exempelvis kan du välja att exkludera annonsering på helger.
					</li>
					<li>
						<strong>Dålig upplevelse av landningssida.</strong><br />nnonserna bör leda till en relevant landningssida på din webbplats där
						innehållet är direkt relaterat till sökordet och annonstexten.
					</li>
				</ol>

				<h3>Kom ihåg!</h3>
				<ul>
					<li><strong>Relevans!</strong><br />Är nyckeln till en lyckad och vinstdrivande annonsering.</li>
					<li><strong>Sökord</strong><br />En väl utförd sökordsanalys säkerställer att du syns på rätt sökning.</li>
					<li>
						<strong>Spårning</strong><br />Spårningen bidrar till värdefull information om vilka sökord som ger önskat resultat. Det är viktigt för
						att kunna mäta och fatta rätt beslut under optimering.
					</li>
				</ul>

				<p>
					Slutligen önskar jag dig lycka till med din marknadsföring, tveka inte att höra av dig ifall du är nyfiken på mer.
				</p>

				<p>Johan Åström, SearchIntent</p>
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
			title: "Blogg | Sökmotormarknadsföring för B2B med 6 tips för bättre annonsering | Rove",
			meta: [
				{
					hid: "description",
					name: "description",
					content:
						"Sökmotorannonsering är en av de kanaler som ger mest “bang for the buck”. I det här inlägget berättar jag mer om SEM och ger sex tips.",
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
