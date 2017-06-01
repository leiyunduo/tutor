<template>
	<div id="app">
		<HeaderView></HeaderView>
		<SectionView></SectionView>
		<FooterView></FooterView>
	</div>
</template>
<script type="text/javascript">
	import HeaderView from './components/Header.vue';
	import SectionView from './components/Section.vue';
	import FooterView from './components/Footer.vue';
	export default{
		components:{
			HeaderView,
			SectionView,
			FooterView
		}
	}
</script>
<style type="text/css">
	@import url("./assets/css/index.css");
</style>