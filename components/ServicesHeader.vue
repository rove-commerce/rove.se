<template>
	<div class="bg-blue pb-10 tablet:pb-12">
		<div class="wrapper page-header flex items-end">
			<div class="inner-wrapper">
				<h3 class="flex items-center text-16 text-pink">
					<icon-symbol-a class="w-3 mr-2"></icon-symbol-a><span><strong>Rove</strong> Methods</span>
				</h3>
				<h1 class="text-pink text-32 tablet:text-48 font-bold leading-tight"><slot></slot></h1>
			</div>
		</div>
	</div>
</template>

<script>
	import IconSymbolA from "~/components/IconSymbolA";

	export default {
		components: {
			IconSymbolA,
		},
	};
</script>
