<script>
	import '../app.postcss';
</script>

<div class="relative w-full h-full overflow-auto">
	<div class="flex flex-col lg:flex-row w-screen h-screen overflow-auto bg-[#090909]">
		<div
			class="h-[77%] lg:w-[56%] lg:h-full bg-no-repeat bg-cover bg-center bg-[url('grunge-overlay-5.png')]"
		/>
		<div class="flex-1 -mt-[47px] lg:-ml-[47px]">
			<span
				class="block left-[100%] lg:top-[100%] h-full w-full top-0 lg:left-0 bg-[url('rip-hor.svg')] lg:bg-[url('rip-vert.svg')] bg-cover"
			/>
		</div>
	</div>
	<div class="absolute top-0 right-0 bottom-0 left-0 overflow-auto"><slot /></div>
</div>
