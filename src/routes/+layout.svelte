<script>
	import '../app.postcss';
</script>

<div class="relative w-screen h-screen">
	<div class="flex w-full h-full bg-[#090909]">
		<div class="w-[58%] bg-no-repeat bg-cover bg-center bg-[url('grunge-overlay-5.png')]" />
		<div class="flex-1 -ml-[47px]">
			<span class="block top-[100%] h-full w-full left-0 bg-[url('rip.svg')] bg-cover" />
		</div>
	</div>
	<div class="absolute top-0 right-0 bottom-0 left-0"><slot /></div>
</div>
