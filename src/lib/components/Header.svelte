<script lang="ts">
	import { Button } from '$lib/components/ui/button';
	import { Menu } from 'lucide-svelte';
	import { X } from 'lucide-svelte';

	let isMenuOpen = false;

	function handleOpenMenu() {
		isMenuOpen = !isMenuOpen;
	}
</script>

<header class="container flex py-11 px-11 sm:py-20 sm:px-20 items-center">
	<div class="flex-1">
		<img src="/logo.svg" alt="" class="max-w-[34px]" />
	</div>
	<nav class="flex items-center">
		<div class="hidden sm:flex">
			<Button
				variant="ghost"
				class="text-[#EABD67] hover:bg-[#4F442F] hover:text-[#EABD67] active:bg-black active:text-[#EABD67] lg:hover:bg-[#B08E4D] lg:active:text-black lg:active:bg-transparent lg:text-sm lg:text-black font-bold px-5 h-8 rounded-none lg:hover:text-black"
				>Home</Button
			>
			<Button
				variant="ghost"
				class="text-[#EABD67] hover:bg-[#4F442F] hover:text-[#EABD67]  active:bg-black active:text-[#EABD67] lg:hover:bg-[#B08E4D] lg:active:text-black lg:active:bg-transparent lg:text-sm lg:text-black font-bold px-5 h-8 rounded-none lg:hover:text-black"
				>Menu</Button
			>
			<Button
				variant="ghost"
				class="text-[#EABD67] hover:bg-[#4F442F] hover:text-[#EABD67]  active:bg-black active:text-[#EABD67] lg:hover:bg-[#B08E4D] lg:active:text-black lg:active:bg-transparent lg:text-sm lg:text-black font-bold px-5 h-8 rounded-none lg:hover:text-black"
				>About Us</Button
			>
		</div>
		<Button
			class="bg-[#EABD67] text-black font-bold hover:bg-[#4F442F] active:bg-[#EABD67] lg:bg-black lg:text-[#EABD67] lg:active:bg-black rounded-none px-8 h-8 ml-3"
			>Log In</Button
		>
		<Button
			variant="ghost"
			class="flex sm:hidden text-[#EABD67] hover:bg-[#4F442F] hover:text-[#EABD67] active:bg-black active:text-[#EABD67] px-2 h-8 ml-1 rounded-none"
			on:click={handleOpenMenu}><Menu /></Button
		>
		<div class="md:hidden">
			{#if isMenuOpen}
				<div
					class="absolute flex flex-col self-end py-11 px-11 space-y-6 font-bold bg-black sm:w-auto sm:self-center left-0 right-0 top-0 bottom-0 drop-shadow-md"
				>
					<div class="flex items-center">
						<div class="flex-1"><img src="/logo.svg" alt="" class="max-w-[34px]" /></div>
						<Button
							variant="ghost"
							class="flex sm:hidden text-[#EABD67] hover:bg-[#4F442F] hover:text-[#EABD67] active:bg-black active:text-[#EABD67] px-2 h-8 ml-1 rounded-none"
							on:click={handleOpenMenu}><X /></Button
						>
					</div>
					<Button
						variant="ghost"
						class="text-[#EABD67] hover:bg-[#4F442F] text-base hover:text-[#EABD67] active:bg-black active:text-[#EABD67] font-bold h-8 rounded-none lg:hover:text-black"
						>Home</Button
					>
					<Button
						variant="ghost"
						class="text-[#EABD67] hover:bg-[#4F442F] text-base hover:text-[#EABD67] active:bg-black active:text-[#EABD67] font-bold h-8 rounded-none lg:hover:text-black"
						>Menu</Button
					>
					<Button
						variant="ghost"
						class="text-[#EABD67] hover:bg-[#4F442F] text-base hover:text-[#EABD67] active:bg-black active:text-[#EABD67] font-bold h-8 rounded-none lg:hover:text-black"
						>About Us</Button
					>
					<Button
						variant="ghost"
						class="text-[#EABD67] hover:bg-[#4F442F] text-base hover:text-[#EABD67] active:bg-black active:text-[#EABD67] font-bold h-8 rounded-none lg:hover:text-black"
						>Log In</Button
					>
				</div>
			{/if}
		</div>
	</nav>
</header>
