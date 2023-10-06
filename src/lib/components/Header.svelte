<script lang="ts">
	import { Button } from '$lib/components/ui/button';
</script>

<header class="container flex py-20 px-20 items-center">
	<div class="flex-1">
		<img src="/logo.svg" alt="" class="max-w-[34px]" />
	</div>
	<nav class="flex items-center">
		<Button variant="ghost" class="text-sm text-black font-bold px-5 h-8 rounded-none">Home</Button>
		<Button variant="ghost" class="text-sm text-black font-bold px-5 h-8 rounded-none">Menu</Button>
		<Button variant="ghost" class="text-sm text-black font-bold px-5 h-8 rounded-none"
			>About Us</Button
		>
		<Button class="rounded-none px-8 h-8 ml-3">Log In</Button>
	</nav>
</header>
