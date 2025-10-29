<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CustomerCardHero from "$lib/components/layout/hero-sections/CustomerCardHero.svelte";
</script>

<CustomerCardHero
	centered={true}
	title="Automate supplier negotiations and save millions"
	subtitle="Sage empowers procurement teams to research suppliers and negotiate contracts intelligently, driving measurable cost savings through automated workflows."
	customers={[
		{
			name: "Sarah Mitchell",
			position: "Procurement Director",
			imageSrc: "/generated/image-documentary-style-environmental-portrait.webp"
		},
		{
			name: "David Chen",
			position: "Operations Manager",
			imageSrc: "/generated/image-candid-environmental-portrait-of-a-profe.webp"
		},
		{
			name: "Jennifer Rodriguez",
			position: "Sourcing Lead",
			imageSrc: "/generated/image-editorial-style-portrait-of-a-profession.webp"
		},
		{
			name: "Michael Thompson",
			position: "Supply Chain Director",
			imageSrc: "/generated/image-documentary-style-portrait-of-a-professi.webp"
		},
		{
			name: "Emily Parker",
			position: "Purchasing Manager",
			imageSrc: "/generated/image-environmental-portrait-of-a-professional.webp"
		}
	]}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/caterpillar.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/3m.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/honeywell.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/emerson.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Intelligent procurement, automated"
	text="Sage transforms how procurement teams at manufacturing companies source suppliers and negotiate contracts. Our platform combines intelligent supplier research with automated negotiation workflows, helping teams secure better pricing and terms while eliminating hours of manual work. The result is millions in documented cost savings and procurement teams freed to focus on strategic decisions rather than repetitive tasks."
/>

<Testimonials
	testimonials={[
		{
			name: "Marcus Williams",
			position: "VP of Procurement",
			company: "Precision Manufacturing",
			quote:
				"Sage reduced our supplier negotiation cycle from 6 weeks to 8 days. We saved $2.3M in our first year by identifying better pricing across our top 50 suppliers. The ROI was undeniable.",
			image: "/generated/image-documentary-style-environmental-portrait.webp"
		},
		{
			name: "Rachel Kowalski",
			position: "Director of Sourcing",
			company: "TechMold Industries",
			quote:
				"Before Sage, my team spent 60% of our time on manual research and spreadsheets. Now we focus on strategic relationships while Sage handles the data analysis. We've cut sourcing costs by 18% while actually improving supplier quality.",
			image: "/generated/image-documentary-style-environmental-portrait.webp"
		},
		{
			name: "Raj Patel",
			position: "Chief Procurement Officer",
			company: "Apex Components",
			quote:
				"The automated negotiation workflows eliminated the risk of missing renewal deadlines. We've avoided $800K in unfavorable auto-renewals and locked in multi-year contracts with 22% better terms than our previous deals.",
			image: "/generated/image-documentary-style-environmental-portrait.webp"
		}
	]}
/>

<Features
	title="Intelligent procurement workflows"
	subtitle="Sage combines AI-driven supplier intelligence with automated negotiation workflows to help procurement teams secure better contracts and drive measurable cost savings."
	features={[
		{
			title: "Intelligent supplier discovery",
			description:
				"Sage automatically identifies and evaluates qualified suppliers based on your specific requirements, historical performance data, and market intelligence. Surface the best suppliers faster and eliminate weeks of manual research."
		},
		{
			title: "Automated negotiation workflows",
			description:
				"Our AI-powered negotiation engine handles contract discussions with suppliers, optimizing terms and pricing based on market benchmarks. Close deals 3x faster while securing better pricing and favorable contract terms."
		},
		{
			title: "Real-time cost optimization",
			description:
				"Track savings opportunities across your entire supply base with intelligent cost analysis and predictive recommendations. Identify millions in potential savings and prioritize high-impact negotiation opportunities."
		},
		{
			title: "Supplier intelligence dashboard",
			description:
				"Consolidate supplier performance metrics, risk indicators, and market trends in one unified view. Make data-driven sourcing decisions with confidence using comprehensive supplier intelligence."
		},
		{
			title: "Contract analytics and benchmarking",
			description:
				"Compare your contract terms against market benchmarks and competitor data to identify favorable pricing opportunities. Leverage market intelligence to strengthen your negotiation position."
		},
		{
			title: "Collaborative sourcing platform",
			description:
				"Enable cross-functional teams to work together seamlessly on sourcing initiatives with shared workflows and audit trails. Improve procurement efficiency and ensure compliance across your organization."
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Start saving on your next supplier contract"
	subtitle="Risk-free pilot with guaranteed savings"
	description="Join procurement teams already saving millions through intelligent automation. Our pilot program guarantees measurable cost savings, so you only move forward when the ROI is proven. See results in weeks, not months."
	imageSrc="/generated/image-documentary-style-environmental-portrait.webp"
	callsToAction={[
		{
			href: "/get-started",
			label: "Start your pilot",
			variant: "primary"
		},
		{
			href: "/contact",
			label: "Talk to our team",
			variant: "secondary"
		}
	]}
/>
