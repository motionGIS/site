<script lang="ts">
	import { Button } from "$lib/components/ui/button";
	import { ArrowRightIcon } from "lucide-svelte";
</script>

<header class="w-full px-6 py-4">
	<div class="container mx-auto flex items-center justify-between max-w-7xl">
		<div class="flex items-center">
			<img src="wordmark.png" alt="motionGIS Logo" class="h-14 px-4" />
			<div class="h-8 w-[3px] bg-border mx-4 lg:mx-8 hidden md:flex"></div>
			<div class="hidden md:flex items-center gap-2 lg:gap-3">
				<a href="https://github.com/motionGIS" target="_blank" class="text-primary hover:text-primary/80 p-2">
                    <img src="icons/github.svg" alt="GitHub" class="w-5 h-5" />
				</a>
				<!--<a href="https://www.youtube.com/@motiongis" target="_blank" class="text-primary hover:text-primary/80 p-2">
					<img src="icons/youtube.svg" alt="YouTube" class="w-5 h-5" />
				</a>-->
				<a href="https://www.linkedin.com/company/motiongis" target="_blank" class="text-primary hover:text-primary/80 p-2">
					<img src="icons/linkedin.svg" alt="LinkedIn" class="w-5 h-5" />
				</a>
			</div>
		</div>

		<div class="flex items-center gap-1 lg:gap-4">
			<nav class="hidden md:flex items-center gap-3 lg:gap-8 font-simply-rounded">
				<a href="tools" class="text-primary hover:text-primary/80 font-medium">software</a>
				<a href="services" class="text-primary hover:text-primary/80 font-medium">services</a>
				<a href="contact" class="text-primary hover:text-primary/80 font-medium">contact</a>
			</nav>
			<div class="h-8 w-[2px] bg-border mx-4 lg:mx-8 hidden md:flex"></div>
			<Button href="tools" class="bg-primary hover:bg-primary/90 text-primary-foreground rounded-full px-6 py-2 font-medium font-simply-rounded">
				try our tools!
				<ArrowRightIcon size={16} class="ml-1 lg:ml-2" />
			</Button>
		</div>
	</div>
</header>
