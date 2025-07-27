<script lang="ts">
	import Header from "$lib/parts/header.svelte";
</script>

<div class="min-h-screen bg-background text-foreground flex flex-col">
	<Header />

	<section class="flex-1 flex flex-col items-center justify-center text-center px-6 py-20">
		<div class="container mx-auto max-w-4xl">
			<!-- Main Heading -->
			<h1 class="text-5xl md:text-6xl lg:text-7xl font-bold text-primary mb-8 leading-tight font-simply-rounded">
				our services
			</h1>

			<!-- Subheading -->
			<p class="text-xl md:text-2xl text-primary font-medium max-w-3xl mx-auto leading-relaxed font-vanilla-extract mb-16">
				we specialize in custom development solutions
				<br />
				tailored to your specific needs.
			</p>

			<!-- Services Content -->
			<div class="max-w-3xl mx-auto text-left">
				<div class="bg-card border border-border rounded-lg p-8 shadow-sm">
					<h2 class="text-3xl font-bold text-primary mb-6 font-simply-rounded">
						commission development
					</h2>
					
					<div class="space-y-4 font-inter text-lg leading-relaxed text-foreground">
						<p>
							We offer custom software development services to bring your unique transportation and GIS solutions to life. Whether you need a specialized mapping application, data analysis tools, or integration with existing systems, our team has the expertise to deliver.
						</p>
						
						<p>
							Our commission development services include:
						</p>
						
						<ul class="list-disc list-inside space-y-2 ml-4">
							<li>Custom web applications and tools</li>
							<li>GIS and mapping solutions</li>
							<li>Transportation data analysis platforms</li>
							<li>API development and system integrations</li>
							<li>Mobile applications for field work</li>
							<li>Data visualization and reporting tools</li>
						</ul>
						
						<p>
							We work closely with our clients throughout the development process to ensure the final product meets your exact specifications and exceeds your expectations.
						</p>
					</div>
					
					<div class="mt-10 pt-8 border-t border-border">
						<p class="text-lg font-medium text-primary font-simply-rounded mb-4">
							Ready to start your project?
						</p>
						<a href="/contact" class="inline-flex items-center bg-primary hover:bg-primary/90 text-primary-foreground rounded-full px-6 py-3 font-medium font-simply-rounded transition-colors">
							Get in touch
							<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="ml-2">
								<path d="M5 12h14"></path>
								<path d="m12 5 7 7-7 7"></path>
							</svg>
						</a>
					</div>
				</div>
			</div>
		</div>
	</section>
</div>
