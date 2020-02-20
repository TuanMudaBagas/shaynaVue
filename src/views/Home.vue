<template>
	<div class="home">
		<Header />
		<Hero />
		<Item />
		<Inta />
		<Brand />
		<Footer />
	</div>
</template>

<script>
import Header from "./../components/Headershayna";
import Hero from "./../components/Heroshayna";
import Item from "./../components/Itemshayna";
import Inta from "./../components/Instashayna";
import Brand from "./../components/Brandshayna";
import Footer from "./../components/Footershayna";
export default {
	name: "Home",
	components: {
		Header,
		Hero,
		Item,
		Inta,
		Brand,
		Footer
	}
};
</script>
