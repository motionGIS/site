<script lang="ts">
	import Header from "$lib/parts/header.svelte";
	import { Button } from "$lib/components/ui/button";
</script>

<div class="min-h-screen bg-background text-foreground flex flex-col">
	<Header />

	<section class="flex-1 flex flex-col items-center justify-center text-center px-6 py-20">
		<div class="container mx-auto max-w-4xl">
			<!-- Main Heading -->
			<h1 class="text-5xl md:text-6xl lg:text-7xl font-bold text-primary mb-8 leading-tight font-simply-rounded">
				get in touch
			</h1>

			<!-- Subheading -->
			<p class="text-xl md:text-2xl text-primary font-medium max-w-3xl mx-auto leading-relaxed font-vanilla-extract mb-16">
				ready to work together?
				<br />
				let's discuss your project.
			</p>

			<!-- Contact Content -->
			<div class="grid md:grid-cols-2 gap-8 max-w-4xl  mx-auto">
			<!-- Contact Information -->
			<div class="bg-card border border-border rounded-lg p-8 h-full shadow-sm text-left flex flex-col">
				<h2 class="text-2xl font-bold text-primary mb-6 font-simply-rounded">
					Contact Information
				</h2>
				
				<div class="space-y-6 font-inter flex-1">
					<div>
						<h3 class="font-medium text-primary mb-2">Email</h3>
						<a href="mailto:hello@motiongis.com" class="text-foreground hover:text-primary transition-colors">
							hello@motiongis.com
						</a>
					</div>
					
					<div>
						<h3 class="font-medium text-primary mb-2">Response Time</h3>
						<p class="text-foreground">
							We typically respond within 24 hours during business days.
						</p>
					</div>
					
					<div>
						<h3 class="font-medium text-primary mb-2">Project Inquiries</h3>
						<p class="text-foreground">
							Include details about your project scope, timeline, and any specific requirements when reaching out.
						</p>
					</div>
				</div>
				
				<div class="mt-10 md:mt-8 pt-8 border-t border-border">
					<h3 class="font-medium text-primary mb-4 font-simply-rounded">Follow Us</h3>
					<div class="flex gap-4">
						<a href="https://github.com/motionGIS" target="_blank" class="text-primary hover:text-primary/80 p-2 border border-border rounded-lg hover:bg-secondary transition-colors">
							<img src="/icons/github.svg" alt="GitHub" class="w-5 h-5" />
						</a>
						<a href="https://www.linkedin.com/company/motiongis" target="_blank" class="text-primary hover:text-primary/80 p-2 border border-border rounded-lg hover:bg-secondary transition-colors">
							<img src="/icons/linkedin.svg" alt="LinkedIn" class="w-5 h-5" />
						</a>
					</div>
				</div>
			</div>				<!-- Quick Contact Form -->
				<div class="bg-card border border-border rounded-lg p-8 shadow-sm text-left">
					<h2 class="text-2xl font-bold text-primary mb-6 font-simply-rounded">
						Send a Message
					</h2>
					
					<form class="space-y-4">
						<div>
							<label for="name" class="block font-medium text-primary mb-2 font-inter">Name</label>
							<input 
								type="text" 
								id="name" 
								name="name" 
								required
								class="w-full px-4 py-3 border border-border rounded-lg bg-background text-foreground focus:ring-2 focus:ring-ring focus:border-transparent transition-colors"
								placeholder="Your name"
							/>
						</div>
						
						<div>
							<label for="email" class="block font-medium text-primary mb-2 font-inter">Email</label>
							<input 
								type="email" 
								id="email" 
								name="email" 
								required
								class="w-full px-4 py-3 border border-border rounded-lg bg-background text-foreground focus:ring-2 focus:ring-ring focus:border-transparent transition-colors"
								placeholder="your@email.com"
							/>
						</div>
						
						<div>
							<label for="subject" class="block font-medium text-primary mb-2 font-inter">Subject</label>
							<input 
								type="text" 
								id="subject" 
								name="subject" 
								required
								class="w-full px-4 py-3 border border-border rounded-lg bg-background text-foreground focus:ring-2 focus:ring-ring focus:border-transparent transition-colors"
								placeholder="Project inquiry"
							/>
						</div>
						
						<div>
							<label for="message" class="block font-medium text-primary mb-2 font-inter">Message</label>
							<textarea 
								id="message" 
								name="message" 
								rows="4" 
								required
								class="w-full px-4 py-3 border border-border rounded-lg bg-background text-foreground focus:ring-2 focus:ring-ring focus:border-transparent transition-colors resize-none"
								placeholder="Tell us about your project..."
							></textarea>
						</div>
						
						<Button type="submit" class="w-full bg-primary hover:bg-primary/90 text-primary-foreground rounded-lg px-6 py-3 font-medium font-simply-rounded">
							Send Message
						</Button>
					</form>
				</div>
			</div>
		</div>
	</section>
</div>
