<template>
	<client-only>
		<div v-if="showCookieBar()" class="bg-white p-4 fixed bottom-0 inset-x-0 border-t border-blue">
			<div class="wrapper flex justify-between items-end">
				<p class="text-14 text-black">
					Den här webbplatsen sparar cookies på din dator. Vissa cookies är nödvändiga för att vår webbplats ska fungera säkert och korrekt, samt för
					att samla in information om hur vår webbplats används. Läs mer i vår
					<nuxt-link to="/privacy/" class="underline">Cookies & Integritetspolicy</nuxt-link>.
				</p>
				<div @click="setCookie" class="btn-blue inline-block cursor-pointer">Tillåt cookies</div>
			</div>
		</div>
	</client-only>
</template>

<script>
	export default {
		data: () => ({
			cookieAccept: false,
		}),
		methods: {
			setCookie() {
				//console.log("setCookie, cookieAccept: " + this.cookieAccept);
				this.$cookies.set("cookie-consent", true);
				this.cookieAccept = true;
			},
			showCookieBar() {
				//console.log("showCookieBar, cookieAccept: " + this.cookieAccept);
				if (this.cookieAccept) {
					return false;
				}
				//console.log("showCookieBar, cookie-consent: " + this.$cookies.get("cookie-consent"));
				if (this.$cookies.get("cookie-consent")) {
					this.cookieAccept = true;
					//console.log("showCookieBar, cookie-consent = true, writing cookieAccept: " + this.cookieAccept);
				}
				return !this.cookieAccept;
			},
		},
	};
</script>
