<script lang="ts">
	import { Button } from '$lib/components/ui/button';
</script>

<header class="container flex py-20 px-20 items-center">
	<div class="flex-1">
		<img src="/logo.svg" alt="" class="max-w-[34px]" />
	</div>
	<nav class="flex items-center">
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
		<Button class="rounded-none px-8 h-8 ml-3">Log In</Button>
	</nav>
</header>
