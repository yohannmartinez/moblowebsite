<script lang="ts">
	import { furnitures } from '$lib/data/furnitures';

	let actualIndex = 1;
</script>

<div
	style="background-image:url('{furnitures[actualIndex].images[0]}')"
	class="relative h-[450px] w-full max-w-[900px] overflow-hidden rounded-3xl bg-black bg-cover bg-center"
>
	<div
		style="background: radial-gradient(59.92% 59.92% at 49.94% 40.08%, rgba(0, 0, 0, 0) 0%, rgba(1, 1, 1, 0.7) 100%);"
		class="absolute left-0 top-0 h-full w-full"
	></div>
	<div class="absolute left-0 top-0 h-full w-full p-4">
		<div class="flex items-end justify-center p-2">
			<div class="flex gap-3">
				{#each furnitures as furniture, furnitureIndex}
					<div
						class="h-1 w-10 rounded-full {actualIndex >= furnitureIndex
							? 'bg-white'
							: 'bg-[#9e9e9e]'}"
					></div>
				{/each}
			</div>
		</div>
	</div>
</div>
