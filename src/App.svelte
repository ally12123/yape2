<script>
	import Router, {location, link} from 'svelte-spa-router';
	import Login from './Login.svelte';
	import Principal from './Principal.svelte';
	import Camara from './Camara.svelte';
	import Yapear from './Yapear.svelte';
	import Yapeado from './Yapeado.svelte';
	import Minsa from './Minsa.svelte';

	const routes = {
		'/': Login,
   		'/Principal/': Principal,
		'/Camara/': Camara,
		'/Yapear/': Yapear,
		'/Yapeado/': Yapeado,
		'/Minsa/': Minsa,
    	'*': Login
	};

</script>

<main>
	<Router {routes}/>
</main>

<style>
	main {
		text-align: center;
		padding: 0;
		margin: 0;
	}
</style>