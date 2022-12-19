<template>
	<div class="bg-pink">
		<div class="wrapper py-20">
			<div class="inner-wrapper flex flex-col tablet-lg:flex-row justify-between items-start">
				<div class="mb-8 tablet-lg:mb-0 tablet-lg:w-1/2">
					<span class="text-blue text-10 uppercase">Kontakta oss</span>
					<h3 class="text-blue text-32">
						<slot> Har du frågor eller vill du prata digital handel med oss?</slot>
					</h3>
				</div>
				<div class="w-full flex flex-col tablet-lg:w-2/5">
					<!-- Netlify forms, remeber to create a static html form for every form used (in "/public/forms") -->
					<form v-bind:name="name" method="POST" netlify data-netlify="true" data-netlify-honeypot="bot-field" action="/form-thank-you/">
						<input type="hidden" name="form-name" v-bind:value="name" />
						<input name="Namn" class="text-input mb-3" type="text" placeholder="Namn*" />
						<input v-if="company === true" name="Företag" class="text-input mb-3" type="text" placeholder="Företag" />
						<input name="Epost" class="text-input mb-3" type="email" placeholder="E-post*" />
						<textarea name="Meddelande" class="textarea mb-5" placeholder="Meddelande"></textarea>
						<button type="submit" class="btn-blue self-center tablet-lg:self-start">Skicka</button>
					</form>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
		props: {
			name: {
				default: "contact",
			},
			company: {
				default: true,
			},
		},
	};
</script>
