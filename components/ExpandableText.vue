<template>
	<div class="border-b border-blue-transparent">
		<div class="flex items-center justify-between cursor-pointer" @click="toggleExpand">
			<span class="block text-blue text-20 font-medium my-3"><slot name="title"></slot></span>
			<icon-chevron-up class="text-blue w-4 mr-4 chevron" ref="chevron"></icon-chevron-up>
		</div>
		<div class="p-3 pt-4 expandable-content" ref="expand">
			<slot name="body"></slot>
		</div>
	</div>
</template>

<script>
	import IconChevronUp from "~/components/IconChevronUp";

	export default {
		components: {
			IconChevronUp,
		},
		props: {
			title: {
				default: "TITLE",
			},
			body: {
				default: "BODY",
			},
		},
		methods: {
			toggleExpand() {
				this.$refs.expand.classList.toggle("active");
				this.$refs.chevron.$el.classList.toggle("expanded");
			},
		},
	};
</script>

<style scoped>
	.expandable-content {
		display: none;
	}
	.expandable-content.active {
		display: block;
	}
	.chevron {
		transition: transform 0.6s cubic-bezier(0.165, 0.84, 0.44, 1);
	}
	.chevron.expanded {
		transform: rotate(180deg);
	}
</style>
