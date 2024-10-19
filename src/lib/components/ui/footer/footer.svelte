<script lang="ts">
	import IconInsta from '~icons/tabler/brand-instagram';
	import IconEtsy from '~icons/tabler/brand-etsy';
	import IconMap from '~icons/tabler/map-pin';
	import Button from '../button/button.svelte';
</script>

<div class="flex w-full justify-center border-t bg-black">
	<div
		class="flex w-full max-w-[900px] flex-col items-center justify-center gap-10 px-9 py-14 md:flex-row md:items-start md:justify-between"
	>
		<div class="flex max-w-[400px] flex-col items-center justify-center gap-5 md:items-start">
			<img src="/logo-min.svg" class=" w-10" />
			<p class="text-center text-sm tracking-tight text-[var(--gray)] md:text-left">
				Moblo Design est une entreprise artisanal 100% Made in France basée à nogent le rotrou,
				remplacer le texte par la vraie description
			</p>
			<p class="text-center text-sm tracking-tight text-[var(--gray)] md:text-left">
				© Tous droits réservés
			</p>
		</div>

		<div class="flex flex-col items-center justify-center gap-2 md:items-start">
			<h1 class="mb-3 text-lg font-semibold tracking-tight">Navigation</h1>
			<span class="text-center text-sm tracking-tight text-[var(--gray)]">Accueil</span>
			<span class="text-center text-sm tracking-tight text-[var(--gray)]">Collection</span>
			<span class="text-center text-sm tracking-tight text-[var(--gray)]">Notre histoire</span>
			<span class="text-center text-sm tracking-tight text-[var(--gray)]">Sur mesure</span>
			<span class="text-center text-sm tracking-tight text-[var(--gray)]">Faq</span>
			<span class="text-center text-sm tracking-tight text-[var(--gray)]">Contact</span>
		</div>

		<div class="flex flex-col items-center justify-center gap-2 md:items-start">
			<h1 class="mb-5 text-lg font-semibold tracking-tight">Liens rapides</h1>
			<Button class="flex min-w-[150px] rounded-full p-6 text-sm font-semibold"
				><IconInsta class="mr-2 text-lg" />Instagram</Button
			>
			<Button class="flex min-w-[150px]  rounded-full p-6 text-sm font-semibold"
				><IconEtsy class="mr-2 text-lg" />Boutique</Button
			>
			<!-- <div>
				<IconMap />
				<span>2 rue des potiers, Nogent-le-rotrou, 28400</span>
			</div> -->
		</div>
	</div>
</div>
