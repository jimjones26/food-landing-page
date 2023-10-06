<script lang="ts">
	import { Button } from '$lib/components/ui/button';
</script>

<header class="container flex py-20 px-20 items-center">
	<div class="flex-1">
		<img src="/logo.svg" alt="" class="max-w-[34px]" />
	</div>
	<nav class="flex space-x-10 text-sm text-black font-bold items-center">
		<a href="/">Home</a>
		<a href="/">Menu</a>
		<a href="/">About Us</a>
		<Button class="rounded-none px-8 h-9">Log In</Button>
	</nav>
</header>
