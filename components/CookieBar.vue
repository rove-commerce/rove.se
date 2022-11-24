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

<script setup>
	const cookieAccept = useCookie("cookie-consent");

	function setCookie() {
		cookieAccept.value = true;
	}

	function showCookieBar() {
		//console.log("showCookieBar, cookieAccept: " + cookieAccept.value);
		if (cookieAccept.value == undefined) {
			return true;
		}
		return !cookieAccept.value;
	}
</script>
