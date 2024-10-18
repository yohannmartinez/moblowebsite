<script>
	import Button from '$lib/components/ui/button/button.svelte';
	import IconCreations from '~icons/tabler/cards';
</script>

<div class="flex w-full items-center justify-center px-6 py-20">
	<div class="flex max-w-[450px] flex-col items-center">
		<img src="/logo.svg" class="mb-16 w-24" alt="Logo de Moblo Design" />
		<p class="mb-5 text-center text-xs font-semibold">
			100% MADE <span class="text-[var(--gray)]">IN FRANCE</span>
		</p>
		<h1 class="mb-5 text-center text-4xl font-bold tracking-tighter sm:text-5xl">
			Moblo Design,<br />phrase d'accroche
		</h1>
		<p class="text-md mb-8 text-center font-semibold tracking-tight">
			Get inspired, discover what’s new in design, and learn from the best <span
				class="text-[var(--gray)]">— all through one weekly email.</span
			>
		</p>
		<Button class="rounded-full p-6 text-sm font-semibold"
			><IconCreations class="mr-2 text-lg" />Collection</Button
		>
	</div>
</div>
