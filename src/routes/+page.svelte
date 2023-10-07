<script lang="ts">
	import Header from '$lib/components/Header.svelte';
	import { Button } from '$lib/components/ui/button';
</script>

<Header />
<section class="flex flex-col px-11 sm:px-20 space-y-6 md:flex-row mb-6">
	<div class="flex flex-col space-y-8">
		<Button class="self-start">Full Menu</Button>
		<h1 class="text-white font-medium text-4xl">Spicy Steaks Turkish Cuisine</h1>
		<p class="text-white text-base">
			Discover the <span class="text-[#EABD67]">BOLD AND SPICY</span> taste of Turkish Cuisine.
		</p>
		<Button class="self-start">Order Online</Button>
		<div class="bg-[#EABD67]/10 p-6 text-white flex space-x-6 justify-center">
			<img src="/dish-1-small.png" alt="" class="w-full h-auto max-w-[106px]" />
			<img src="/dish-1-small.png" alt="" class="w-full h-auto max-w-[106px]" />
			<img src="/dish-1-small.png" alt="" class="w-full h-auto max-w-[106px]" />
		</div>
	</div>
	<img src="/dish-1-big.png" alt="" class="w-full h-full max-w-[535px] md:ml-10" />
</section>
