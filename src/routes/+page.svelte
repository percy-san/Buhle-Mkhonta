
<script type="text/javascript">
	import Hero from '$lib/components/Hero.svelte'
	import Services from '$lib/components/Services.svelte'
	import Skills from '$lib/components/Skills.svelte'
	import Work from '$lib/components/Work.svelte'
	import Contact from '$lib/components/contact.svelte'
	


	
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
	<div id="contact">
		<Contact/>
	</div>

	<div class="to-top" uk-tooltip="Go To Top">
		<a href="/" uk-totop uk-scroll></a>
	</div>
	

</main>

<style type="text/css">
	main{
		display: grid;
	}

	#hero,#services,#skills, #work,#contact{
		padding: 40px;

	}
	
	
	#services,#work{
		background: var(--gray);
	}

	.to-top{
		position: fixed;
		bottom: 20px;
		right: 20px;
		padding: 10px;
		text-align: center;
		background: var(--myRed);
		z-index: 1;
		
	}
	.to-top:hover{
		background: var(--hoverRed);
	}

	.to-top a{
		color: white;
		font-weight: bold
	}
	@media screen and (max-width: 900px) {
		

	
	}
	
</style>