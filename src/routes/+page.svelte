
<script type="text/javascript">
	import Hero from '$lib/components/Hero.svelte'
	import Services from '$lib/components/Services.svelte'
	import Skills from '$lib/components/Skills.svelte'
	import Work from '$lib/components/Work.svelte'
	


	
</script>


<svelte:head>
	<title>Home-Buhlebethu Mkhonta</title>
</svelte:head>

<main>
	<div id="hero">
		<Hero />
	</div>

	<div id="services">
		<Services />
	</div>
	<div id="skills">
		<Skills />
	</div>
	<div id="work">
		<Work/>
	</div>

</main>

<style type="text/css">
	main{
		display: flex;
		flex-direction: column;
		
	}

	#hero,#services,#skills, #work{
		padding: 40px;

	}
	
	#services,#work{
		background: var(--gray);


		

	}
	@media screen and (max-width: 900px) {
		

	
	}
	
</style>