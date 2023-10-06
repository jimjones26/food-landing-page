<script>
	import '../app.postcss';
</script>

<div class="relative w-screen h-screen">
	<div class="flex flex-col md:flex-row w-full h-full bg-[#090909]">
		<div
			class="h-[58%] md:w-[58%] md:h-full bg-no-repeat bg-cover bg-center bg-[url('grunge-overlay-5.png')]"
		/>
		<div class="flex-1 -mt-[47px] md:-ml-[47px]">
			<span
				class="block left-[100%] md:top-[100%] h-full w-full top-0 md:left-0 bg-[url('rip-hor.svg')] md:bg-[url('rip-vert.svg')] bg-cover"
			/>
		</div>
	</div>
	<div class="absolute top-0 right-0 bottom-0 left-0"><slot /></div>
</div>
