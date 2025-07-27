<script lang="ts">
	import Header from "$lib/parts/header.svelte";
	import { Button } from "$lib/components/ui/button";
	import { ExternalLinkIcon, GithubIcon, FileTextIcon, PackageIcon } from "lucide-svelte";
</script>

<div class="min-h-screen bg-background text-foreground flex flex-col">
	<Header />

	<section class="flex-1 px-6 py-20">
		<div class="container mx-auto max-w-6xl">
			<!-- Main Heading -->
			<div class="text-center mb-16">
				<h1 class="text-5xl md:text-6xl lg:text-7xl font-bold text-primary mb-8 leading-tight font-simply-rounded">
					our tools
				</h1>
				<p class="text-xl md:text-2xl text-primary font-medium max-w-3xl mx-auto leading-relaxed font-vanilla-extract">
					open source tools for transportation,
					<br />
					mapping, and data visualization.
				</p>
			</div>

			<!-- Tools Grid -->
			<div class="grid md:grid-cols-2 xl:grid-cols-3 gap-8">
				
				<!-- Fast Line Heatmap -->
				<div class="bg-card border border-border rounded-lg p-6 shadow-sm hover:shadow-md transition-shadow">
					<div class="flex items-start justify-between mb-4">
						<h3 class="text-2xl font-bold text-primary font-simply-rounded">fast-line-heatmap</h3>
						<FileTextIcon size={20} class="text-primary opacity-60" />
					</div>
					
					<p class="text-foreground font-inter mb-6 leading-relaxed">
						High-performance library for generating line-based heatmaps with WebAssembly acceleration. Available across multiple package managers with academic backing.
					</p>
					
					<!-- Technologies -->
					<div class="mb-6">
						<h4 class="text-sm font-medium text-primary mb-3 font-simply-rounded">Technologies</h4>
						<div class="flex flex-wrap gap-2">
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">Rust</span>
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">WebAssembly</span>
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">JavaScript</span>
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">Python</span>
						</div>
					</div>
					
					<!-- Links -->
					<div class="space-y-3">
						<div class="flex flex-wrap gap-2">
                            <Button size="sm" variant="default" class="text-xs" href="https://activityheatmap.pages.dev/" target="_blank">
								<ExternalLinkIcon size={14} class="mr-1" />
								Demo
							</Button>
							<Button size="sm" variant="outline" class="text-xs" href="https://crates.io/crates/heatmap-parse" target="_blank">
								<PackageIcon size={14} class="mr-1" />
								crates.io
							</Button>
							<Button size="sm" variant="outline" class="text-xs" href="https://www.npmjs.com/package/heatmap-parse" target="_blank">
								<PackageIcon size={14} class="mr-1" />
								npm
							</Button>
							<!--<Button size="sm" variant="outline" class="text-xs">
								<PackageIcon size={14} class="mr-1" />
								PyPI
							</Button>-->
                            <Button size="sm" variant="outline" class="text-xs" href="https://github.com/a0a7/fast-line-heatmap" target="_blank">
								<GithubIcon size={14} class="mr-1" />
								GitHub
							</Button>
							<Button size="sm" variant="outline" class="text-xs" title="in the publishing process. page will be updated soon">
								<FileTextIcon size={14} class="mr-1" />
								Technical Paper
							</Button>
						</div>
					</div>
				</div>

				<!-- rMap -->
				<div class="bg-card border border-border rounded-lg p-6 shadow-sm hover:shadow-md transition-shadow">
					<div class="flex items-start justify-between mb-4">
						<h3 class="text-2xl font-bold text-primary font-simply-rounded">rMap</h3>
						<ExternalLinkIcon size={20} class="text-primary opacity-60" />
					</div>
					
					<p class="text-foreground font-inter mb-6 leading-relaxed">
						Convenient tool for generating images of subdivisions & broad regions of the US & Canada with support for displaying GPX data.
					</p>
					
					<!-- Technologies -->
					<div class="mb-6">
						<h4 class="text-sm font-medium text-primary mb-3 font-simply-rounded">Technologies</h4>
						<div class="flex flex-wrap gap-2">
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">Svelte</span>
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">TypeScript</span>
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">Tailwind CSS</span>
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">MapLibre GL</span>
						</div>
					</div>
					
					<!-- Links -->
					<div class="flex gap-2">
						<Button href="https://rmap.a0.ax" target="_blank" size="sm" class="bg-primary hover:bg-primary/90 text-primary-foreground">
							<ExternalLinkIcon size={14} class="mr-1" />
							Visit Site
						</Button>
						<Button size="sm" variant="outline" href="https://github.com/motionGIS/RegionMapGenerator" target="_blank">
							<GithubIcon size={14} class="mr-1" />
							GitHub
						</Button>
					</div>
				</div>

				<!-- Stats for Garmin -->
				<div class="bg-card border border-border rounded-lg p-6 shadow-sm hover:shadow-md transition-shadow">
					<div class="flex items-start justify-between mb-4">
						<h3 class="text-2xl font-bold text-primary font-simply-rounded">Stats for Garmin</h3>
						<ExternalLinkIcon size={20} class="text-primary opacity-60" />
					</div>
					
					<p class="text-foreground font-inter mb-6 leading-relaxed">
						Advanced analytics and visualization tool for Garmin device data, providing insights into your fitness and activity patterns.
					</p>
					
					<!-- Technologies -->
					<div class="mb-6">
						<h4 class="text-sm font-medium text-primary mb-3 font-simply-rounded">Technologies</h4>
						<div class="flex flex-wrap gap-2">
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">Svelte</span>
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">TypeScript</span>
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">Tailwind CSS</span>
						</div>
					</div>
					
					<!-- Links -->
					<div class="flex gap-2">
						<Button href="https://garmin.a0.ax/" target="_blank" size="sm" class="bg-primary hover:bg-primary/90 text-primary-foreground">
							<ExternalLinkIcon size={14} class="mr-1" />
							Visit Site
						</Button>
						<Button size="sm" variant="outline" href="https://github.com/a0a7/GymStats" target="_blank">
							<GithubIcon size={14} class="mr-1" />
							GitHub
						</Button>
					</div>
				</div>

				<!-- Strava Tools -->
				<div class="bg-card border border-border rounded-lg p-6 shadow-sm hover:shadow-md transition-shadow">
					<div class="flex items-start justify-between mb-4">
						<h3 class="text-2xl font-bold text-primary font-simply-rounded">strava.tools</h3>
						<ExternalLinkIcon size={20} class="text-primary opacity-60" />
					</div>
					
					<p class="text-foreground font-inter mb-6 leading-relaxed">
						Comprehensive toolkit for analyzing and visualizing Strava activity data with advanced plotting and statistical analysis capabilities.
					</p>
					
					<!-- Technologies -->
					<div class="mb-6">
						<h4 class="text-sm font-medium text-primary mb-3 font-simply-rounded">Technologies</h4>
						<div class="flex flex-wrap gap-2">
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">Svelte</span>
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">TypeScript</span>
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">Tailwind CSS</span>
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">Observable Plot</span>
						</div>
					</div>
					
					<!-- Links -->
					<div class="flex gap-2">
						<Button href="https://strava.a0.ax" target="_blank" size="sm" class="bg-primary hover:bg-primary/90 text-primary-foreground">
							<ExternalLinkIcon size={14} class="mr-1" />
							Visit Site
						</Button>
						<Button href="https://github.com/a0a7/strava.tools" target="_blank" size="sm" variant="outline">
							<GithubIcon size={14} class="mr-1" />
							GitHub
						</Button>
					</div>
				</div>

				<!-- Svelte Multi-Activity Heatmap -->
				<div class="bg-card border border-border rounded-lg p-6 shadow-sm hover:shadow-md transition-shadow">
					<div class="flex items-start justify-between mb-4">
						<h3 class="text-2xl font-bold text-primary font-simply-rounded">Multi-Activity Heatmap</h3>
						<ExternalLinkIcon size={20} class="text-primary opacity-60" />
					</div>
					
					<p class="text-foreground font-inter mb-6 leading-relaxed">
						Interactive heatmap visualization for multiple activity types, built with modern web technologies and mapping libraries.
					</p>
					
					<!-- Technologies -->
					<div class="mb-6">
						<h4 class="text-sm font-medium text-primary mb-3 font-simply-rounded">Technologies</h4>
						<div class="flex flex-wrap gap-2">
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">Svelte</span>
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">TypeScript</span>
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">Tailwind CSS</span>
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">MapLibre GL</span>
						</div>
					</div>
					
					<!-- Links -->
					<div class="flex gap-2">
						<Button href="https://stravamap.pages.dev/" target="_blank" size="sm" class="bg-primary hover:bg-primary/90 text-primary-foreground">
							<ExternalLinkIcon size={14} class="mr-1" />
							Visit Site
						</Button>
						<Button size="sm" variant="outline" href="https://github.com/a0a7/StravaMultiMapper" target="_blank">
							<GithubIcon size={14} class="mr-1" />
							GitHub
						</Button>
					</div>
				</div>

				<!-- Transit Fare Card Map -->
				<div class="bg-card border border-border rounded-lg p-6 shadow-sm hover:shadow-md transition-shadow">
					<div class="flex items-start justify-between mb-4">
						<h3 class="text-2xl font-bold text-primary font-simply-rounded">Transit Fare Card Map</h3>
						<ExternalLinkIcon size={20} class="text-primary opacity-60" />
					</div>
					
					<p class="text-foreground font-inter mb-6 leading-relaxed">
						Interactive map showcasing transit fare card systems across different regions, providing insights into public transportation payment methods.
					</p>
					
					<!-- Technologies -->
					<div class="mb-6">
						<h4 class="text-sm font-medium text-primary mb-3 font-simply-rounded">Technologies</h4>
						<div class="flex flex-wrap gap-2">
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">Svelte</span>
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">TypeScript</span>
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">Tailwind CSS</span>
							<span class="px-3 py-1 bg-secondary text-secondary-foreground rounded-full text-sm font-medium">MapLibre GL</span>
						</div>
					</div>
					
					<!-- Links -->
					<div class="flex gap-2">
						<Button href="https://transitcards.a0.ax" target="_blank" size="sm" class="bg-primary hover:bg-primary/90 text-primary-foreground">
							<ExternalLinkIcon size={14} class="mr-1" />
							Visit Site
						</Button>
						<Button size="sm" variant="outline" href="https://github.com/a0a7/TransitCardsMap" target="_blank">
							<GithubIcon size={14} class="mr-1" />
							GitHub
						</Button>
					</div>
				</div>

			</div>

			<!-- Bottom CTA -->
			<div class="mt-16 text-center">
				<div class="bg-card border border-border rounded-lg p-8 max-w-2xl mx-auto">
					<h2 class="text-3xl font-bold text-primary mb-4 font-simply-rounded">
						Need Something Custom?
					</h2>
					<p class="text-foreground font-inter mb-6 leading-relaxed">
						All of our tools are open source, but we also offer custom development services for specialized transportation and mapping solutions.
					</p>
					<div class="flex gap-4 justify-center">
						<Button href="/services" class="bg-primary hover:bg-primary/90 text-primary-foreground rounded-full px-6 py-3 font-medium font-simply-rounded">
							View Services
						</Button>
						<Button href="/contact" variant="outline" class="rounded-full px-6 py-3 font-medium font-simply-rounded">
							Contact Us
						</Button>
					</div>
				</div>
			</div>
		</div>
	</section>
</div>
