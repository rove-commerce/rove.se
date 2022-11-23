<template>
	<div>
		<main-navigation @toggle-navigation="toggleNavigation"></main-navigation>
		<blog-post-body>
			<template v-slot:author>Henrik Lundin</template>
			<template v-slot:date>15 April 2020</template>
			<template v-slot:title>
				Ordlista för e-handel B2B
			</template>
			<template v-slot:body>
				<p>
					Nu kör vi igång med vår e-handelsskola B2B e-handel för nybörjare! Innan vi hoppar in och börjar prata om hur vi attraherar, konverterar och
					får lojala kunder ska vi börja med att förklara viktiga begrepp och termer, en ordlista för B2B e-handel.
				</p>
				<p>
					<strong> 3PL</strong>: 3PL betyder tredjepartslogistik, man lägger ut lagerhantering och delar av Fulfillment-processen hos en tredjepart.
					3PL är ett intressant alternativ för många verksamheter som inte kan eller vill ha eget lager.
				</p>

				<p>
					<strong> 404</strong>: 404-sidor är sidor på en webbplats där det inte finns något innehåll, sidan finns inte. Antingen har det funnits
					innehåll på adressen tidigare som flyttats eller raderats eller så har besökaren skrivit in fel adress. Man vill fånga upp besökare som
					kommit till en 404-sida på din webbplats och leda dom rätt så att dom inte omedelbart lämnar webbplatsen, därför brukar man lägga lite kraft
					på att presentera bra innehåll på 404-sidor.
				</p>
				<p>
					<strong> A/B-testa</strong>: A/B-testa eller "splittesta" innebär att man testar och mäter mellan ett eller flera alternativ (alternativ A,
					alternativ B osv), ofta handlar det om hur ens webbplats och e-handel ser ut i små detaljer, exempelvis placering av knappar, eller vilket
					innehåll som leder till fler avslut. Att splittesta är för många e-handlare grunden i ett datadrivet mindset, "innan man testat vet man
					inte".
				</p>
				<p><strong> AdWords</strong>: Google Ads är Googles plattform för annonsering. Den hette fram till 2018 Google AdWords.</p>
				<p>
					<strong> Affärssystem</strong>: affärssystemet är "hjärtat" i ett företags IT-stöd. Där hanteras ekonomifunktionen, fakturering och
					kundreskontra, löner, inköp och i de flesta fall även lagerhantering, orderhantering, grundläggande produktinformation, returer och
					reklamationer. Affärssystem kallas ibland även för "ERP" - Enterprise Resource Planning.
				</p>
				<p>
					<strong> Alibaba</strong>: Alibaba är en kinesisk företagsgrupp med den gigantiska handelsplatsen Alibaba.com och shoppingsajten taobao.com
					i spetsen. Alibaba har även en sökmotor och en rad andra datadrivna tjänster. Alibaba finns inte i Sverige.
				</p>
				<p>
					<strong> Amazon</strong>: Amazon är både en molntjänstplattform (se AWS) och världens näst största e-handlare (sett till total omsättning är
					Alibaba nu större). Amazon har en dominant position i Nordamerika och har även ett starkt fäste på flera europeiska marknader (men finns
					ännu inte i Sverige). Amazon är en marknadsplats där (nästan) vem som helst kan sälja sina varor. Svenska bolag kan sälja på Amazon till de
					marknader där Amazon finns och kan även använda sig av Amazons omfattande lager- och logistiklösningar för att lagra och skeppa till kunder
					på dessa marknader. Amazons e-handelslösning riktar sig både till konsumenter (B2C) och handel mellan företag (B2B).
				</p>
				<p>
					<strong> Avvisningsfrekvens</strong>: En avvisning är en besökare som bara (under en och samma session) besöker en sida och därpå lämnar din
					webbplats. Avvisningsfrekvens är hur många procent av besökssessionerna som är avvikelser. I Google Analytics kan du se den totala
					avvisningsfrekvensen för din webbplats med rapporten "Översikt över målgrupp". Rapporten "Alla sidor" visar avvisningsfrekvensen för
					enskilda sidor.
				</p>
				<p>
					<strong> AWS</strong>: Amazon Web Services (AWS) är en Amazons molntjänstplattform som används för att driva (hosta, drifta) applikationer
					och SaaS-tjänster (Software as a Service). Istället för att drifta sina system själva kan man flytta dom till AWS (eller motsvarande
					lösningar, exempelvis Google Cloud och Microsoft Azure).
				</p>
				<p>
					<strong> Betald trafik</strong> (eller "sponsrad trafik"): med betald trafik menas besök som du betalt för via digital annonsering,
					vanligtvis Google Ads. Motsatsen till betald trafik är organisk trafik, se "Organisk trafik" nedan.
				</p>
				<p><strong> Bounce rate</strong>: engelska för Avvisningsfrekvens, se "Avvisningsfrekvens" ovan.</p>
				<p>
					<strong> Call-to-Action</strong>: en Call-to-Action (CTA) är en uppmaning till handling, ofta tänkt att användas för att leda en besökare
					vidare ner i marknads- och säljtratten, exempelvis genom att erbjuda besökaren på din webbplats att ladda ner ett whitepaper i utbyte mot
					kontaktuppgifter. En bra marknadstratt / webbplats har tydliga call-to-actions i alla flöden och på alla sidor så att besökaren leds vidare
					till kontakt eller avslut. Besökaren ska alltid erbjudas ett nästa steg.
				</p>
				<p>
					<strong> Canonical link</strong> (svenska: "Kanonisk URL"): om en produkt finns publicerad i flera kategorier ska en webbplats berätta för
					sökmotorer vilken kategori som är produktens huvudkategori. Detta göras genom att i e-handelsplattformen eller CMS-systemet peka ut
					huvudkategorin för en produkt. Om man inte använder sig av kanoniska länkar kommer sökmotorer se det som duplicerat innehåll vilket ger
					sämre länkkraft (du får mindre organisk trafik).
				</p>
				<p>
					<strong> Checkout</strong>: engelska för kassa. Kassan i en e-handel är där kunden kan se en sammanställning av, och ändra i, sin
					order/kundvagn för att slutligen bekräfta ordern och gå vidare till nästa steg i köpprocessen (vanligtvis betalning eller
					leveransalternativ).
				</p>
				<p>
					<strong> Click & Collect</strong>: Click & Collect betyder att man köper eller reserverar i e-handeln och sedan själv hämtar varan i butik
					eller hos handlaren.
				</p>
				<p>
					<strong> CMS</strong>: CMS är engelska för "Content Management System". Med ett CMS hanterar man sin webbplats och dess innehåll. Det finns
					fristående CMS och CMS-moduler i e-handelsplattformar.
				</p>
				<p>
					<strong> Content Marketing</strong>: engelska för innehållsmarknadsföring. Innehållsmarknadsföring är en marknadsföringsmetod för att nå ut
					till sin målgrupp genom relevant innehåll på mottagarens villkor. Ofta handlar det om redaktionellt innehåll (exempelvis en artikel) för att
					driva trafik till företagets kanaler (exempelvis företagets webbplats). Denna bloggpost är ett bra exempel. Mottagaren hittar oftast
					innehållet genom en sökning i en sökmotor, via rekommendation eller via sociala media och leds sedan vidare i företagets marknads- och
					säljtratt.
				</p>
				<p>
					<strong> Cookie</strong>: en cookie ("kaka" på svenska) är en liten fil som lämnas på din dator efter att du har besökt en webbplats. När du
					besöker webbplatsen igen skickas cookien med tillbaka till webbplatsen, på så sätt kan man se om besökaren är en återkommande besökare och
					till viss mån spara information om besökaren.
				</p>
				<p>
					<strong> CRM</strong>: CRM står för "Customer Relationship Management" och är en arbetsprocess för försäljning, marknadsföring och kundvård
					(och ibland även service/kundtjänst) där kunden är det centrala begreppet. CRM-system är ett IT-system för att hantera information om
					processen och kunderna samt verktyg för försäljning, marknadsföring och service.
				</p>
				<p>
					<strong> Direkttrafik</strong>: besök där besökaren har gått direkt till din webbplats genom att skriva in din webbadress direkt eller har
					bokmärkt en sida på din webbplats, till skillnad från att använda en sökmotor eller klicka på en länk på en annan webbplats som leder till
					din webbplats.
				</p>
				<p>
					<strong> Drop shipping</strong>: Drop shipping innebär att man inte själv lagerför en produkt utan att produkten levereras direkt från en
					leverantör till din kund när den beställs på din e-handel.
				</p>
				<p>
					<strong> E-handelsplattform</strong>: det IT-system/IT-tjänst som hanterar ett företags e-handel. E-handelsplattformen är ofta integrerad
					med företagets affärssystem.
				</p>
				<p><strong> ERP</strong>: se Affärssystem.</p>
				<p>
					<strong> Facetterad navigation, filter och sök</strong>: facetterad navigation innebär att besökaren i flera steg kan förfina sin sökning /
					sitt urval genom att kombinera sök, filter och kategorival. Exempelvis först söka på "Adidas", sedan välja kategori "Byxor", därefter välja
					"Storlek = 50", därefter "Färg = blå".
				</p>
				<p>
					<strong> Filter</strong>: med hjälp av filter kan en besökare hitta fram till rätt produkter på en e-handel genom att exkludera produkter
					som inte passar in på filtret. Man kan exempelvis filtrera produkter på färg, pris, kategori, lagertillgänglighet och andra produktattribut.
				</p>
				<p>
					<strong> Fraud</strong>: engelska för bedrägeri. Bedrägerier är vanligt förekommande inom e-handel och det sker en ständig utveckling av nya
					bedrägerimetoder och motmedel.
				</p>
				<p>
					<strong> GDPR</strong> (General Data Protection Regulation): EUs nya förordning om hur man får behandla personuppgifter. På svenska heter
					den "Dataskyddsförordningen" (DSF).
				</p>
				<p>
					<strong> Google Ads</strong>: Googles plattform för annonsering. Google Ads används mestadels ihop med Googles sökmotor. Köpare betalar för
					att deras annons ska visas när utvalda sökord används. Produktannonser för tjänsten Google Shopping heter "Product Listing Ads", se PLA
					nedan, och är en del av Google Ads. Att arbeta med annonser i sökmotorer benämns SEA (Search Engine Advertising), se SEA nedan.
				</p>
				<p>
					<strong> Google Analytics</strong>: Googles verktyg för analys och uppföljning av besök, mål och handel på en webbplats, ett livsviktigt
					verktyg för alla e-handlare. Standardversionen av Google Analytics är kostnadsfri, observera dock att du ger Google tillgång till din data.
					Google Analytics kan användas på alla webbplatser och i alla e-handelsplattformar. Om det inte finns en färdig koppling är det enkelt att
					ordna, man lägger till en liten kodsnutt på din webbplats.
				</p>
				<p>
					<strong> Google Shopping</strong>: Google Shopping är Googles sök-/annonstjänst för produkter. Tidigare har Google Shopping hetat Google
					Product Search, Google Products och Froogle. Handlare annonserar sina produkter på Google Shopping varpå de visas i vanliga Google-sökningar
					och under fliken "Shopping". När besökaren klickar på en produkt eller väljer att besöka butiken kommer man till produkten på handlarens
					webbplats (och Google får betalt). Produktannonser kallas "Product Listing Ads" (PLA).
				</p>
				<p><strong> Ingångssida</strong>: se "Landningssida".</p>
				<p><strong> Kassa</strong>: se Checkout ovan.</p>
				<p>
					<strong> Kategorisida</strong>: en kategorisida på en e-handel listar alla produkter i produktkategorin och har också eget innehåll (texter,
					bilder etc). Kategorisidor är ofta landningssidor på en e-handel.
				</p>
				<p>
					<strong> Konverteringsgrad</strong> (engelska: "conversion rate"): konverteringsgraden i e-handelssammanhang är hur många procent av
					besökssessionerna (se Session nedan) som resulterar i ett avslut (ofta en orderläggning) = (Antal besök med 1 eller fler avslut)/(Totalt
					antal besök). Totalt antal besök avser oftast det totala antalet besök under en period, inte bara från unika besökare (se Unika besökare
					nedan).
				</p>
				<p>
					<strong> Kundresa</strong> (engelska: "customer journey"): en kundresa beskriver hela den resa en kund gör från probleminsikt och kännedom
					om ert företag hela vägen till första köp och hur kunden blir en lojal återkommande kund. Att arbeta med kundresan är ett viktigt verktyg om
					man vill arbeta kundcentriskt. Kundresan beskriver hur kunden agerar och vad som är viktigt för kunden ur ett utifrån-och-in-perspektiv i
					varje steg, så att ni kan mappa era interaktioner, tjänster, processer, systemstöd och organisation utifrån detta. Läs mer om kundresan i
					vår metod Fomm Methods Kundresan.
				</p>
				<p>
					<strong> Kundvagn</strong> (engelska: "shopping cart" eller bara "cart"): besökare stoppar varor i sin kundvagn innan de går till kassan.
					Ofta sparas de varor besökaren har i kundvagnen tills nästa besök om man inte genomför ett köp.
				</p>
				<p>
					<strong> Lagersaldo</strong>: med lagersaldo menas oftast hur många leveransklara produkter man har kvar i sitt lager, som inte är
					reserverade för någon annan, .
				</p>
				<p>
					<strong> Landningssida</strong>: den sida som en besökare först kommer till ("landar") på din webbplats under en besökssession kallas för
					landningssida. Landningssidor kallas även för "ingångssidor". Man behöver veta vilka dessa sidor är och lägga extra prioritet på att de
					funkar och leder besökaren rätt. Vanligtvis är startsidan den vanligaste landningssidan, men även produktkategorisidor, innehållssidor som
					du länkar till från innehållskampanjer är vanliga landningssidor. I Google Analytics kallas landningssidor för "ingångssidor" och under
					"Beteende - Webbplatsinnehåll" kan du se vilka dina viktigaste landningssidor är.
				</p>
				<p>
					<strong> Lead</strong>: ett lead är ett tips om en affär och är ett av de första stegen i köpresan. Ett lead kan vara ett tips om en
					nykundsaffär eller affär mot en befintlig kund. Lead brukar ofta kvalificeras för att sedan utvecklas vidare till affärstillfällen och
					slutligen affär.
				</p>
				<p>
					<strong> Lead Generation</strong>: Lead Generation är processen för att generera leads till marknads- och säljtratten och är vanligtvis en
					av marknadsteamets huvuduppgifter i B2B-företag. Kvalificerade leads lämnas sedan över till säljteamet för att där utvecklas till
					affärstillfällen och slutligen affärer.
				</p>
				<p>
					<strong> Marketing Automation</strong>: Marketing Automation (MA) är processen för att automatisera interaktionen med och marknadsföringen
					till din målgrupp. Genom automatisering är målet att kunna rikta rätt budskap till rätt person vid rätt tillfälle, något som är snudd på
					omöjligt om man arbetar manuellt. Man vill komma bort från opersonlig masskommunikation, bli mer relevant och kunna hantera flera på
					varandra följande interaktioner. Konkret handlar det om att beskriva ett interaktionsflöde i ett Marketing Automation-system, besökaren gör
					så här, då ska detta skickas till besökaren, och klickar sedan besökaren i e-postmeddelandet så ska detta hända osv.
				</p>
				<p>
					<strong> Marknadsplats</strong>: en digital marknadsplats är en e-handelsplats där sortimentet består av produkter från många olika säljare,
					som kund kan jag se och jämföra mellan flera leverantörer. Marknadsplatsen hanterar ofta hela flödet, orderhantering, betalning, logistik,
					möjlighet att kunna köpa från flera säljare på samma order etc. Marknadsplatser finns både för B2C och B2B, generella (exempelvis CDON eller
					Amazon) eller branschspecifika.
				</p>
				<p>
					<strong> Marknadstratten</strong> (även kallad "marknads- och säljtratten", engelska: "Marketing / Sales Funnel"): Marknadstratten är den
					process i vilket man gör nya affärer. Marknadstratten har flera steg, den är bred högt upp där man har många interaktioner och en spets
					längst ned där man stänger affärer. Stegen ser lite olika ut beroende på bransch men oftast handlar det om att skapa intresse och
					interaktion högst upp, därefter fånga upp de intressanta som "leads", kvalificera dessa till konkreta "affärstillfällen" som sedan ska
					stängas till affär.
				</p>
				<p>
					<strong> Minicart</strong>: en minicart visar kundvagnens innehåll när besökaren håller musmarkören över kundvagnsikonen på en e-handel, man
					ser vad som är i kundvagnen utan att behöva klicka och gå till kassan.
				</p>
				<p>
					<strong> Navigation</strong>: i webbsammanhang syftar Navigation på hur en besökare hittar, navigerar på en webbsida. Oftast handlar det om
					sökfunktion, menyer, filter och länkar.
				</p>
				<p>
					<strong> On-Site search</strong>: "On-site search" är sökfunktionen på din webbplats, till skillnad från en publik sökmotor som exempelvis
					Google som söker på alla webbplatser.
				</p>
				<p>
					<strong> Orderstatus</strong>: en order som läggs går igenom flera olika steg där varje steg beskrivs med ett orderstatus. Det första steget
					brukar vara att ordern är "bekräftad", därefter ska den "packas", den blir "betald", "levererad" osv.
				</p>
				<p>
					<strong> Organisk trafik</strong>: organisk trafik (engelska: "Organic traffic" eller "Earned traffic") är trafik till din webbplats som du
					inte betalt för. Motsatsen till organisk trafik är betald trafik (se "Betald trafik" ovan). Organisk trafik kommer oftast ifrån sökmotorer
					(s.k. organisk sök), direkttrafik (när man skriver in din webbadress direkt eller har bokmärkt din sida) eller hänvisningstrafik (engelska:
					"Referral traffic") när andra webbplatser länkar till dig.
				</p>
				<p>
					<strong> Persona</strong> (engelska "buyer persona"): för att säkerställa att ens marknadsbudskap träffar rätt hos de viktigaste
					målgrupperna är det viktigt att ta fram "typpersoner" hos dina målgrupper, gärna hos din idealkund. Det kan exempelvis vara den typiska
					inköpschefen, dess roll, befogenheter, motivationsfaktorer och beslutsbarriärer. Allt innehåll man tar fram bör riktas till en eller flera
					av dessa personas. I vår metod Fomm Methods Kundresan inleder vi arbetet med att ta fram personas.
				</p>
				<p>
					<strong> Personalisering</strong> (engelska: "personalization"): Personalisering är ett vitt begrepp men det brukar handla om att rikta
					relevant budskap till rätt person/målgrupp, istället för samma budskap till alla. Helst vill man att varje person ska få ett skräddarsytt
					"personligt" budskap (s.k. "1:1") men det kan även handla om personalisering på gruppnivå, exempelvis ort, kundgrupp, ett visst beteende mm.
				</p>
				<p>
					<strong> PIM</strong>: PIM står för "Product Information Management" och är en arbetsprocess för att hantera produktinformation. Ett
					PIM-system är ett IT-system för att hantera information om produkterna och få ut produktinformationen till de kanaler där de ska visas.
					PIM-processen innefattar att berika produkterna med information (få in all information om produkterna i systemet), planera vart produkterna
					ska publiceras och slutligen publicera produkterna till rätt kanal och målgrupp, gärna med så stor automatik som möjligt. Det finns
					fristående PIM-system och e-handelsplattformar som har inbyggd PIM-funktionalitet.
				</p>
				<p><strong> PLA</strong>: Engelsk förkortning för "Product Listing Ad" på Google Shopping, se "Google Shopping" ovan.</p>
				<p>
					<strong> Plocklager</strong>: ett plocklager är ett lager där varorna är ordnade så att man effektivt kan plocka varor styckvis till en
					order, varorna ligger inte samlade i pallar (det kallas "bulklager").
				</p>
				<p>
					<strong> Produktrekommendationer</strong>: med produktrekommendationer menas att presentera utvalda produkter för en besökare, om möjligt
					med ett individuellt urval med hjälp av personaliseringsfunktioner (se "Personalisering" ovan) eller styrt utefter besökarens beteende. Ofta
					handlar det om viktiga ytor på en webbplats där man vill visa utvalda produkter, exempelvis på startsidan eller på kategorisidor.
				</p>
				<p>
					<strong> Produktkategori</strong>: för att underlätta för besökaren att hitta på en e-handel brukar man dela upp produkterna i kategorier,
					exempelvis "Borrar" och "Hyllor". Kategorier kan ha underkategorier och samma produkt kan finnas i flera kategorier. Om en produkt finns i
					flera kategorier är det viktigt ur SEO-synpunkt att berätta för sökmotorer vilken som är produktens huvudkategori, se "Canonical links"
					ovan. Kategorier är också viktiga landningssidor med eget innehåll.
				</p>
				<p>
					<strong> Produktsida</strong> (eller "Produktdetaljsida"): den sida på en e-handel som visar all information om en enskild produkt eller
					variant av produkt. Varje produkt/variant bör ha en egen unik URL (se "URL" nedan).
				</p>
				<p>
					<strong> Produktvariant</strong>: När en produkt finns i flera utföranden kallas de varianter, exempelvis en t-shirt som finns i flera
					färger och storlekar. Varje variant är på alla sätt en egen produkt, med eget artikelnummer, lagerställe, pris etc men har till viss del
					samma information som de andra varianterna.
				</p>
				<p>
					<strong> Punch out</strong>: Med en "Punch out"-lösning kan en beställare påbörja ett köp i sitt eget inköpssystem för att sedan slussas
					vidare till leverantörens e-handel där man plockar ihop sin varukorg. Varukorgen skickas sedan tillbaka till inköpssystemet där ordern
					attesteras och slutförs.
				</p>
				<p>
					<strong> Retargeting</strong> (eller Remarketing): När en besökare tittar på en produkt på din webbplats kan du visa en betald annons för
					samma produkt på andra webbplatser med en länk tillbaka din webbplats. Man annonserar alltså om en produkt som kunden redan tittat på hos
					dig. Retargeting funkar så att en cookie lagras i besökarens webbläsare med vilken produkt besökaren tittat på hos dig. Cookien skickas
					sedan med till andra webbplatser där det finns annonsplatser, exempelvis med Google Ads, Facebook och i displaynätverk såsom Aftonbladet.
					Man "förföljer" alltså besökaren där den surfar med annonser på produkter besökaren tittat på tidigare.
				</p>
				<p>
					<strong> SEA</strong>: SEA betyder sökmotorsannonsering och är engelska för "Search Engine Advertising", man arbetar med att driva trafik
					till sin webbplats (se "Betald trafik" ovan) genom att köpa annonser som visas i sökresultatet när vissa sökfraser används.
				</p>
				<p>
					<strong> SEM</strong>: SEM betyder sökmotormarknadsföring och är engelska för "Search Engine Marketing". SEM innefattar alla aspekter av
					marknadsföring för sökmotorer, både organisk ("SEO") och betald ("SEA").
				</p>
				<p>
					<strong> SEO</strong>: SEO betyder sökmotoroptimering och är engelska för "Search Engine Optimization". Inom SEO arbetar man med att skapa
					organisk trafik till sin webbplats genom att optimera innehållet på webbplatsen för att den ska hamna så högt upp som möjligt i
					sökmotorernas organiska sökresultat.
				</p>
				<p>
					<strong> Session</strong> (eller "Besökssession"): när en besökare kommer till din webbplats påbörjar denne en ny session. En session kan
					innehålla flera sidvisningar, dvs att besökaren klickar sig vidare till flera sidor på din webbplats i samma session. I Google Analytics
					gäller att om en besökare är inaktiv på din webbplats i 30 minuter eller mer, registreras framtida aktivitet som en ny session. Besökare som
					lämnar din webbplats och återkommer inom 30 minuter räknas som en del av den ursprungliga sessionen. Sessioner är inte detsamma som
					"användare", en och samma användare kan genomföra flera sessioner på en webbplats.
				</p>
				<p><strong> SoMe</strong>: en förkortning för "Sociala Media"; Facebook, Instagram mfl.</p>
				<p><strong> Splittesta</strong>: Se "A/B-testa" ovan.</p>
				<p>
					<strong> Tullager</strong>: Om du importerar varor kan du använda ett tullager för att slippa betala tull och andra skatter och avgifter på
					dina produkter förrän de faktiskt säljs (när man tar varorna ur lagret), man får på så sätt ett bättre kassaflöde. Varor i ett tullager är
					oförtullade tills dess de lämnar lagret. Om varorna ska vidare till Norge slipper du betala tullkostnad vid import till Sverige om de lagras
					i ett tullager.
				</p>
				<p>
					<strong> Unika besökare</strong> (eller "unika användare" eller bara "användare"): om en besökare besöker din webbplats flera gånger under
					en period räknas det bara som en unik besökare, det är sammas "person" (egentligen är det samma cookie/webbläsare). En unik besökare kan
					alltså göra flera besök under en period.
				</p>
				<p>
					<strong> URL</strong>: URL (engelska: "Uniform Resource Locator") är en internetadress som identifierar en viss webbsida eller resurs
					(filer, bilder etc) på nätet, exempelvis "https://www.jollyroom.se/fritid-hobby/utelek/hoverboards/impulse-hoverkart". I e-handelssammanhang
					är URL:er viktiga, det ska vara lätt att länka till en specifik produkt- eller kategorisida och URL:ens innehåll tros ha betydelse för hur
					väl sökmotorer rankar en sida.
				</p>
				<p>
					<strong> Utgångssida</strong> (eller "utgångar"): den sista sida som en besökare var på i en session innan de lämnade din webbplats.
					Utgångssidor är viktiga att ha koll på, så att man förstår om det är någon sida som inte funkar där besökare ofta lämnar webbplatsen. Man
					kan se utgångssidor i Google Analytics under "Beteende - Webbplatsinnehåll".
				</p>
				<p>
					<strong> Återkommande besökare</strong>: en återkommande besökare är en person (egentligen webbläsare) som redan tidigare i samma period har
					besökt din webbplats, de har "återkommit".
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
			title: "Blogg | Ordlista för e-handel B2B | Rove",
			meta: [
				{
					hid: "description",
					name: "description",
					content: "Ordlista för B2B e-handel och digital marknadsföring: betydelse, exempel, definition och enkla förklaringar.",
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
