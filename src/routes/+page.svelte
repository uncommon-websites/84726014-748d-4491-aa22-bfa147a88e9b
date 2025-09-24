<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Transform recruiting from manual screening bottlenecks into automated talent pipelines"
	subtitle="AI agents that continuously evaluate and match candidates, empowering healthcare staffing agencies to fill critical roles 5x faster with 80% less manual work."
	imageSrc="/generated/image-healthcare-recruiting-manager-30s-confid.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/nursefinders.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/aya.healthcare/w/400/h/400/logo',
		'https://cdn.brandfetch.io/cross-country-healthcare.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/flexcare.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Maria Rodriguez",
			position: "VP Operations",
			company: "CareNational Staffing",
			quote:
				"Harmony has been the highlight of my year. We've reduced our time-to-placement by 80% and now fill critical nursing positions in 48 hours instead of weeks. The AI agents work around the clock, so we never miss qualified candidates.",
			image: "/generated/image-professional-headshot-of-maria-rodriguez.webp"
		},
		{
			name: "David Chen",
			position: "Director of Talent Acquisition",
			company: "Allied Healthcare Solutions",
			quote:
				"Before Harmony, our recruiters spent 15+ hours weekly screening unqualified applicants. Now they save 10 hours per week and focus on building relationships with our best candidates. It's transformative technology we didn't know we needed.",
			image: "/generated/image-professional-headshot-of-david-chen-seni.webp"
		},
		{
			name: "Aisha Thompson",
			position: "Operations Manager",
			company: "Premier Health Staffing",
			quote:
				"The semantic search capability is game-changing. Instead of keyword matching, Harmony's AI understands what we actually need and surfaces 5x more qualified applicants. We're filling positions faster than our competitors and our clients notice the difference.",
			image: "/generated/image-professional-headshot-of-aisha-thompson-.webp"
		}
	]}
/>

<Features
	generating
	title="Features"
	subtitle="Some features"
	features={[
		{
			title: "Streamlined Workflows",
			description:
				"Automate repetitive tasks and connect systems to improve productivity with our industry-leading 87% time savings."
		},
		{
			title: "Data Analysis",
			description:
				"Extract meaningful insights from your data with powerful analytical tools backed by proprietary AI algorithms that are 3x more accurate than competitors."
		},
		{
			title: "Secure Collaboration",
			description:
				"Work together seamlessly while maintaining strict data privacy standards with our zero-knowledge architecture and military-grade encryption."
		}
	]}
/>
<AboutTeaser />
<CallToAction generating />
