<template>
	<div class="bg-pink">
		<div class="wrapper py-20">
			<div class="inner-wrapper flex flex-col tablet-lg:flex-row justify-between items-start">
				<div class="mb-8 tablet-lg:mb-0 tablet-lg:w-1/2">
					<span class="text-blue text-10 uppercase">Kontakta oss</span>
					<h3 class="text-blue text-32">
						<slot>
							Har du frågor eller vill du prata digital handel med oss? Underbart!
						</slot>
					</h3>
				</div>
				<div class="w-full flex flex-col tablet-lg:w-2/5">
					<!--<script charset="utf-8" type="text/javascript" src="//js.hsforms.net/forms/shell.js"></script>-->
					<div id="embedded-form" />

					<!-- Old solution with Netlify forms, remeber to create a static html form for every form used (in "/static/forms") 
					<form v-bind:name="name" method="POST" data-netlify="true" data-netlify-honeypot="bot-field" action="/form-thank-you/">
						<input type="hidden" name="form-name" v-bind:value="name" />
						<input name="Namn" class="text-input mb-3" type="text" placeholder="Namn*" />
						<input name="Företag" class="text-input mb-3" type="text" placeholder="Företag" />
						<input name="Epost" class="text-input mb-3" type="email" placeholder="E-post*" />
						<textarea name="Meddelande" class="textarea mb-5" placeholder="Meddelande"></textarea>
						<button type="submit" class="btn-blue self-center tablet-lg:self-start">
							Skicka
						</button>
					</form>
					-->
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
		},

		mounted() {
			window.hbspt.forms.create({
				portalId: "8359383",
				formId: "0bad4780-c02d-4f07-b9be-e11fcb437de0",
				target: "#embedded-form",
			});
		},
	};
</script>
