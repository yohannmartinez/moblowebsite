<script lang="ts">
	import Box from '$lib/components/ui/box/box.svelte';
	import FurnituresCarousel from '$lib/components/ui/furnituresCarousel/furnituresCarousel.svelte';
	import IconChevron from '~icons/tabler/chevron-right';
</script>

<div style="background: var(--white-linear-background)" class="pb-20">
	<div class="flex flex-col items-center justify-center gap-7 px-7">
		<div class="flex w-full max-w-[900px] flex-col gap-7 md:flex-row">
			<Box
				pinColor="#68cc58"
				title="Notre histoire"
				subTitle="Découvrir"
				imageUrl="https://moblomedias.s3.eu-north-1.amazonaws.com/global/wood.avif"
			/>

			<Box
				pinColor="#fc7840"
				title="Sur mesure"
				subTitle="Nouveau"
				imageUrl="https://moblomedias.s3.eu-north-1.amazonaws.com/global/story.avif"
			/>
		</div>

		<FurnituresCarousel />

		<div class="flex w-full max-w-[900px] flex-col gap-7 md:flex-row">
			<Box
				pinColor="#f2c94c"
				title="Sur mesure"
				subTitle="Nouveau"
				imageUrl="https://moblomedias.s3.eu-north-1.amazonaws.com/global/test.avif"
			/>
			<Box
				pinColor="#5e6ad2"
				title="Contact"
				subTitle="Découvir"
				imageUrl="https://moblomedias.s3.eu-north-1.amazonaws.com/global/test.avif"
			/>
		</div>
	</div>
</div>
