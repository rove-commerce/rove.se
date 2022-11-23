<template>
	<div class="bg-orange py-20">
		<div class="wrapper">
			<div class="inner-wrapper">
				<div>
					<!-- Promoted blog post -->
					<span class="block text-blue text-10 uppercase mb-2">Blogg</span>
					<NuxtLink to="/blogg/upphandla-ehandelsprojekt/">
						<div class="text-blue text-20 leading-normal mb-4 laptop:text-32">
							Ska du upphandla ett e-handelsprojekt? <br />Problem-topplistan och hur du bör göra istället.
						</div>
					</NuxtLink>
					<read-link to="/blogg/upphandla-ehandelsprojekt/"></read-link>

					<!-- 3 blog posts -->
					<!-- First post -->
					<div class="flex flex-col laptop:flex-row pt-6">
						<div class="laptop:w-1/3 py-6 laptop:px-4 py-1 border-t laptop:border-l laptop:border-t-0 border-blue">
							<span class="block text-blue text-10 uppercase mb-2">Blogg</span>
							<NuxtLink to="/blogg/punchout/">
								<h3 class="text-blue text-20 leading-normal mb-4">
									PunchOut e-handel - öppna en ny försäljningskanal till era kunder
								</h3>
							</NuxtLink>
							<read-link to="/blogg/punchout/"></read-link>
						</div>

						<!-- Second post -->
						<div class="laptop:w-1/3 py-6 laptop:px-4 py-1 border-t laptop:border-l laptop:border-t-0 border-blue laptop:ml-4">
							<span class="block text-blue text-10 uppercase mb-2">Blogg</span>
							<NuxtLink to="/blogg/kanalkonflikter/"
								><h3 class="text-blue text-20 leading-normal mb-4">
									Sälja direkt och kanalkonflikter
								</h3>
							</NuxtLink>
							<read-link to="/blogg/kanalkonflikter/"></read-link>
						</div>

						<!-- Third post -->
						<div class="laptop:w-1/3 py-6 laptop:px-4 py-1 border-t laptop:border-l laptop:border-t-0 border-blue laptop:ml-4">
							<span class="block text-blue text-10 uppercase mb-2">Blogg</span>
							<NuxtLink to="/blogg/organisation-ehandel-b2b-2/">
								<h3 class="text-blue text-20 leading-normal mb-4">
									Del 2 - Vilken organisation behövs för en B2B e-handel?
								</h3>
							</NuxtLink>
							<read-link to="/blogg/organisation-ehandel-b2b-2/"></read-link>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
	import ReadLink from "~/components/ReadLink";

	export default {
		components: {
			ReadLink,
		},
	};
</script>
