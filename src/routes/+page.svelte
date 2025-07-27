<script lang="ts">

	import Header from "$lib/parts/header.svelte";
</script>

<div class="min-h-screen bg-background text-foreground flex flex-col">
	<Header />

<section class="flex-1 flex flex-col items-center justify-center text-center px-6 py-20">
	<div class="container mx-auto max-w-6xl">
		<h1 class="text-6xl md:text-7xl lg:text-8xl font-bold text-primary mb-12 leading-tight font-simply-rounded">
			get around <span class="italic font-light font-simply-rounded relative inline-block">
				smarter
				<span class="absolute bottom-[14px] lg:bottom-[17px] left-0 w-full h-5 bg-primary opacity-40 transform rotate-[-3deg] rounded skew-x-50"></span>
			</span>
		</h1>

		<p class="text-xl md:text-2xl text-primary font-medium max-w-3xl mx-auto leading-relaxed font-vanilla-extract">
			we create intelligent tools to enable
			<br />
			better transportation choices.
		</p>
	</div>
</section>
</div>
