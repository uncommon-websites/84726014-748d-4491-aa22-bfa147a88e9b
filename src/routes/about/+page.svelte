<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "AI-powered intelligence",
			description: "We deploy cutting-edge AI agents that understand context, not just keywords, transforming manual screening into intelligent talent pipelines."
		},
		{
			title: "Recruiter empowerment",
			description: "Our technology amplifies human expertise by handling repetitive tasks, freeing recruiters to focus on building meaningful connections with top talent."
		},
		{
			title: "Continuous improvement",
			description: "We iterate relentlessly based on real-world results, constantly enhancing our platform to deliver measurable improvements in time-to-hire and candidate quality."
		},
		{
			title: "Healthcare specialization",
			description: "We understand the unique challenges of healthcare staffing, from critical role urgency to complex credential requirements, building solutions that work in your world."
		}
	];
</script>

<SecondaryHero
	title="Let AI do the screening"
	subtitle="So your team can hire faster"
	imageSrc="/generated/image-photorealistic-candid-photo-of-a-diverse.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"We started in 2018 with a simple goal: make helpful tech that people actually need. While many chase profits, we chose to do things differently.",
		"Beyond making good products, we care about doing the right thing, being kind to our planet, and making sure everyone can use what we build. That's our compass.",
		"From day one, we've asked ourselves: 'Does this actually help people?' This question gets us through tough calls and shapes who we are. We're playing the long game here.",
		"We think about how our work affects real people's lives. We build tech that brings people together, keeps your information safe, and treats everyone fairly. When we stick to these basics, good things happen."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- Team and investors sections removed as no actual data available -->

<!-- CTA Section -->
<CallToAction
	title="Ready to transform your recruiting?"
	subtitle="Join healthcare leaders choosing AI"
	description="Stop spending 15+ hours weekly screening unqualified candidates. Join VP Operations at leading healthcare staffing agencies who've already discovered the future of talent acquisition."
	imageSrc="/generated/image-photorealistic-candid-scene-of-a-healthc.webp"
/>
