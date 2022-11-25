<template>
    <div>
        <main-navigation @toggle-navigation="toggleNavigation"></main-navigation>
        <blog-post-body>
            <template v-slot:author>Henrik Lundin</template>
            <template v-slot:title>
                Trender, tips och fallgropar för digital handel B2B
            </template>
            <template v-slot:body>
                <p>
                    Webinar från den 10 mars 2020.
                </p>
                <p>
                    E-handelsplattformen Litium bjöd in mig för att hålla ett Webinar om trender, erfarenheter och
                    vanliga misstag för digital B2B-handel. Härligt, mitt favoritämne alla kategorier.
                </p>
                <p>
                    Alltid spännande att prata trender, det som slår mig är hur snabbt det kan gå i vår bransch, en
                    trend kan snabbt omsättas i realitet och få ett stort genomslag. Det jag lyfter fram i Webinaret är
                    <ul>
                        <li>Marknadsplatser för B2B, möjligheter och hot</li>
                        <li>En himla massa kanaler, vi behöver vara lyhörda för hur kunden vill agera och i vilka
                            kanaler</li>
                        <li>Digital natives, vikten av en bra användarupplevelse hos den nya generationen kunder och
                            kollegor</li>
                        <li>Sälja direkt, allt fler går förbi mellanledan och öppnar direktkanaler till slutkunden,
                            varför och är det en bra idé?</li>
                        <li>AI, närmare bestämt Machine Learning, vilka tillämpningar finns och vad är viktigt att tänka
                            på?</li>
                    </ul>
                </p>
                <p>
                    Utifrån dessa trender och ett kundreseperspektiv diskuterar vi viktiga erfarenheter och fallgropar,
                    bl.a. vikten att göra en (enkel) kartläggning av kundresan, betydelsen av UX för B2B, de viktigaste
                    användarfallen och vad man ska tänka på för ett framgångsrik införande. Enjoy!
                </p>
                <p>Ta del av Webinaret <a href="https://youtu.be/lJJbQxdC0nw" rel="noopener" target="_blank">här</a>:
                    <iframe width="740" height="416" src="https://www.youtube.com/embed/lJJbQxdC0nw" frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen>
                    </iframe>
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
			title: "Blogg | Trender, tips och fallgropar för digital handel B2B | Rove",
			meta: [
				{
					hid: "description",
					name: "description",
					content:
						"Webinar från den 10 mars 2020. E-handelsplattformen Litium bjöd in mig för att hålla ett Webinar om trender, erfarenheter och vanliga misstag för digital B2B-handel.",
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
