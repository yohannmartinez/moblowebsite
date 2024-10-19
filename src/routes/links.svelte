<script lang="ts">
	import Box from '$lib/components/ui/box/box.svelte';
	import Button from '$lib/components/ui/button/button.svelte';
	import IconCreations from '~icons/tabler/cards';
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

		<div
			class="relative h-[90vh] w-full max-w-[900px] overflow-hidden rounded-3xl bg-black bg-[url('https://moblomedias.s3.eu-north-1.amazonaws.com/global/furnitures-group.avif')] bg-cover bg-bottom"
		>
			<div
				class="flex h-full w-full flex-col items-center justify-center bg-[radial-gradient(circle_farthest-corner_at_50%_50%,#0a0a0a_2%,#0a0a0a20)] px-10"
			>
				<h1 class="m-8 text-center text-6xl font-semibold tracking-tighter">Signé Moblo</h1>
				<p class="text-md mb-8 max-w-[400px] text-center font-semibold tracking-tight">
					Get inspired, discover what’s new in design, and learn from the best <span
						class="text-[var(--gray)]">— all through one weekly email.</span
					>
				</p>
				<Button class="mb-5 rounded-full p-6 text-sm font-semibold"
					><IconCreations class="mr-2 text-lg" />Collection</Button
				>
			</div>
		</div>

		<div class="flex w-full max-w-[900px] flex-col gap-7 md:flex-row">
			<Box
				pinColor="#f2c94c"
				title="FAQ"
				subTitle="Une question"
				imageUrl="https://moblomedias.s3.eu-north-1.amazonaws.com/global/review2.avif"
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
