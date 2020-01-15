<template>
	<q-page>
		<Carosuel />
		<ProductMain/>
		<WhyUs />
		<AboutUs />
		<ContactUs />
	</q-page>
</template>
<script>
	import Carosuel from '../components/Carosuel.vue'
	import ProductMain from '../components/ProductMain.vue'
	import ContactUs from '../components/ContactUs.vue'
	import AboutUs from '../components/AboutUs.vue'
	import WhyUs from '../components/WhyUs.vue'
export default
{
	name: 'PageIndex',
	components:
	{
		Carousel,
		AboutUs,
		ContactUs,
		WhyUs,
		ProductMain
	}
};

</script>
