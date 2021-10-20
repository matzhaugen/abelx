<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
	import Counter from '$lib/Counter.svelte';
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<section>
	<h1>
		<div class="welcome" >
			Abel X
		</div>
	</h1>

</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center bottom;
		align-items: center;
		flex: 1;	
	}

	h1 {
		width: 100%;
	}

	.welcome {
		height: 550px;
		width: 1000px;
		background: url(senja.jpg) center top;
		background-repeat: no-repeat;
		background-size: 900px;
		background-attachment: fixed;
		font-size: 10rem;
		text-align: center;
		/*line-height: 200px;*/

	}

</style>
