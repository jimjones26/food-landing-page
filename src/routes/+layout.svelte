<script>
	import '../app.postcss';
</script>

<div class="relative w-screen h-screen">
	<div class="flex w-full h-full">
		<div
			class="w-[58%] bg-no-repeat bg-cover bg-center bg-[#090909] bg-[url('grunge-overlay-5.png')]"
		/>
		<div class="bg-[#EABD67] flex-1" />
	</div>
	<div class="absolute top-0 right-0 bottom-0 left-0"><slot /></div>
</div>
