<script>
	import Router, {location} from 'svelte-spa-router';
	import Home from './Home.svelte';
	import Mattysbox from './Mattysbox.svelte';
</script>

<Router routes={{
	'/Home': Home,
	'/Mattysbox': Mattysbox
}} />


<!-- SWITCH OVER TO SVELTE-NAVIGATOR INSTEAD, NO HASH ROUTES, THEY SCREW WITH POP UP -->