<script lang="ts">
	import IconChevron from '~icons/tabler/chevron-right';
	export let title: string;
	export let subTitle: string;
	export let imageUrl: string;
	export let pinColor: string;
</script>

<div
	style="background-image:url('{imageUrl}')"
	class="box-border flex h-80 w-full cursor-pointer items-end justify-between rounded-3xl bg-black bg-cover bg-bottom p-8"
>
	<div>
		<div class="mb-2 flex items-center">
			<div style="background-color:{pinColor}" class="mr-2 h-2 w-4 rounded-full bg-[]"></div>
			<span class="text-sm font-medium tracking-tight text-[var(--gray)]">{subTitle}</span>
		</div>
		<h1 class="text-2xl font-semibold tracking-tight">{title}</h1>
	</div>
	<div class="rounded-full border p-3"><IconChevron /></div>
</div>
