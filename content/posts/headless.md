---
title: För- och nackdelar med Headless - ur ett kundperspektiv
description: Headless e-handel - fördelar och nackdelar ut ett kundperspektiv
---

## Headless e-handel - vad betyder det?

Headless e-handel eller inte? Integrerat system eller monolit? Det är en stundtals hetsk debatt med argument som i många fall inte alls utgår från kundens faktiska behov. Det blir ofta en ren teknikdiskussion där andra perspektiv tappas bort.

Headless e-handel innebär att de tekniska lösningarna för försäljningskanalerna ("storefront" på engelska) är skiljda från e-handelssystemet där e-handelsfunktioner och affärsreglerna finns. En försäljningskanal kan exempelvis vara en e-handelswebbplats, en mobilapp eller en fysisk butik. De tekniska lösningarna för försäljningskanalerna kommunicerar med e-handelssystemet via dess API:er. Man säger då att e-handelssystemet är headless för att det i sig inte innehåller försäljningskanalerna, de är fristående och kan komma från olika leverantörer.

## Kort om tekniken

Tittar man närmare på headless ur ett tekniskt perspektiv inser man att det handlar om tre saker:

1. Dela upp sin IT-arkitektur i mindre självständiga komponenter.
2. API:er blir viktiga, API:er är det som kopplar ihop de olika komponenterna. API:erna ska vara teknikoberoende så att vilket system som helst, oavsett vilken teknik det är byggd med, kan användas sig av dem. Man blir mer "API-centrisk" än "systemcentrisk" i sin IT-arkitektur.
3. Möjlighet att använda olika teknologier för de olika kanalerna, för att skapa bästa möjliga användarupplevelse för varje kanal.

I själva verket är det den API-centriska arkitekturen som är det viktiga här, headless är då en naturlig följd som uppstår pga av att de olika systemen är oberoende och kommunicerar via API:er.

Ett typiskt exempel på headless e-handel är när man har ett e-handelssystem där affärsreglerna finns och en webbplats som använder sig av e-handelssystemets funktioner via dess API. Via API:et kan webbplatsen säga åt e-handelssystemet att skapa en order, fråga vilka kampanjer som är aktiva osv. E-handelssystemet och webbplatsen är oberoende av varandra, båda system kan bytas ut så länge API:ets "kontrakt" finns kvar. Vill man lägga på en försäljningskanal till använder den också e-handelssystemets API, helt oberoende av andra kanaler.

En viktig sak att påpeka är att ett e-handelssystem både kan ha API:er för andra kanaler, samtidigt som det själv innehåller några "inbyggda" kanaler. Det handlar alltså inte om allt eller inget. Det är tvärtom vanligt att e-handelssystem har vissa kanaler inbyggda, och erbjuder övriga API:er. Det viktiga är då att funktioner och affärsregler är lika både för de inbyggda kanalerna som för de som använder API:erna. Det är den API-centriska arkitekturen som är det viktiga, inte att e-handelssystemet absolut inte får ha inbyggda kanaler.

## Headless CMS och PIM

Men vänta lite, en försäljningskanal behöver inte bara affärsregler utan också information om alla produkter och övrigt innehåll, texter och bilder ("content"). Med andra ord, om en försäljningskanal ska vara oberoende och fristående som behöver den även kunna hämta all produktinformation och all annan content via API:er. Det är alltså inte bara e-handelssystemet som behöver vara headless för att det hela ska fungera, även PIM-system och CMS-system behöver exponera sin data och funktionalitet via API:er, antingen som en del av e-handelssystemet eller som fristående system.

## Fördelar

Ok, vilka är då kundfördelarna med en headless-arkitektur (API-centrisk)?

### 1. Försäljning i flera kanaler

Det starkaste argumentet för att välja en API-centrisk arkitektur är om man säljer i flera olika kanaler där olika kanaler behöver olika typer av system, exempelvis för att sälja via sin webbplats, en mobilapp och en marknadsplats. Varje kanal kan ha sin egen tekniska lösning samtidigt som affärsreglerna och informationen behöver vara densamma över alla kanaler, exempelvis samma produktinformation, priser och kampanjer. Vart en order läggs spelar ingen roll, samma affärsregler gäller. Kanalerna behöver utgå från samma data, exempelvis kan en kund lägga en order i en kanal och göra en retur i en annan kanal.

För de som säljer i flera kanaler (om man inte kan hitta ett e-handelssystem som har färdig funktionalitet för alla de kanaler man behöver) är därför en API-centrisk arkitektur vettig, det är API:erna som blir viktiga och man kan använda olika specialiserade lösningar för varje kanal. Om e-handelssystemet man väljer har några inbyggda kanaler är det bara bra, så länge man inte är låsta till de inbyggda kanalerna och har API:er för övriga kanaler.

### 2. Speciella UX-behov

Det vanligaste skjälöet

-   Speciella UX behov
-   Plattformsoberoende / befintligt CMS
-   Prestanda och säkerhet
-   Tydliga roller och ansvar

## Nackdelar

-   Högre kostnader, både initialt och för vidareutveckling
-   Kräver mer teknikkompetens
-   Färre färdiga moduler och integrationer (exempel klarna och söktjänst som behöver integreras både front-end och back-end)
-   Marknadsavdelningen jobbar med kanalneutralt content, markup mm
-   Svårare att få ett grepp om analys när data är utspridd i olika system (men det finns lösningar), exempelvis kombinerade rapporter från försäljning, besöksstatistik och sök, vilka sökfraser gav mest försäljning och vilka sökningar funkade inte?

## Sammanfattning

-   För de som jobbar i flera kanaler på riktigt, säljer man primärt via webben är det svårare att motivera
-   Passar de med egen inhouse-utveckling (kräver kompetens inom Javascript / NodeJS och UX). Nämna Markup?
-   Kräver en stor omställning för marknads- och contentteam
-   Undvik fallgropen med att en teknikbyrå vill införa headless för teknikens skull

Var nämner jag Composable Commerce?
