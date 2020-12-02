<template>
	<div>
		Hello! {{hero.firstName}}
	</div>
</template>

<script>
	export default {
		name: 'HeroDetail',
		props: {
		  hero: {
		    type: Object, // String, Number, Boolean, Function, Object, Array
		    default: ()=>{},
		  },
		},
	};
</script>


