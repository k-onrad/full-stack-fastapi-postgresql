<script>
	import Topbar from '../components/Topbar.svelte'
  import Sidebar from '../components/Sidebar.svelte'

	export let segment
</script>

<style>
	main {
		position: relative;
		max-width: 56em;
		background-color: white;
    padding-top: 4.64286rem;
    padding-left: 0;
    padding-right: 0;
    padding-bottom: 0;
    margin: 0;
	}
</style>

<Topbar {segment}/>

<main>
  <Sidebar/>
	<slot></slot>
</main>
