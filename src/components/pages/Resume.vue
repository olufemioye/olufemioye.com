<template>
	<div class="page page--grid">
		<section class="page-content">
			<div class="page-content__container">
				<h1 class="heading" data-aos="fade-up" data-aos-duration="800" data-aos-delay="200">Resume</h1>
				<p class="paragraph text-steel margin-b-lg" data-aos="fade-up" data-aos-duration="600" data-aos-delay="400">I have over 4 years of experience in building world-class digital products that help people and businesses succeed.</p>
				<section class="margin-b-lg" data-aos="fade-up" data-aos-duration="600" data-aos-delay="600">
					<h4 class="sub-heading">Work Experience</h4>
					<Timeline date="Mar. 2020 - Present" 
										role="UX Developer | VC4A"
										description="Connecting entrepreneurs with investors with code and design."  />
					<Timeline date="Feb. 2018 - Mar. 2020" 
										role="Product Designer | REACH"
										description="Designed tools and solutions that helps millennials understand, borrow and invest money." />
					<Timeline date="Aug. 2016 - Feb. 2018" 
										role="Front-end Developer | SeamlessHR"
										description="Developed various products that empowers and enhances HR systems and career development."  />
				</section>
				
				<section>
					<h4 class="sub-heading">Education</h4>
					<Timeline date="Bachelor of Science 2016" 
										role="Obafemi Awolowo University"
										description="Chemical Engineering."  />
				</section>
				
			</div>
		</section>
		<section class="page-visual" data-aos="fade" data-aos-duration="1200" data-aos-delay="800">
			<div class="page-visual__container">
				<ResumeEnvelope />
			</div>
		</section>
	</div>
</template>

<script>
	import Timeline from "@/components/snippets/Timeline.vue";
	import ResumeEnvelope from "@/components/snippets/ResumeEnvelope";

	export default {
		name: 'Resume',
		components: {
			Timeline,
			ResumeEnvelope
		}
	}
</script>