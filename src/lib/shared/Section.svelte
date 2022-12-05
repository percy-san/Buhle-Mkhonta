<script type="text/javascript">
	export let heading
	export let number 
	export let bottomText
	
	
</script>

<main>
	<div>
		<p class="heading"><span>{number}</span>{heading}</p>
		<h3 class="bottom-text">{bottomText}</h3>
		
		
	</div>

</main>

<style type="text/css">
	main{
		text-align: center;
		padding-bottom: 20px;
	}
	
	.heading{
		color: white;
		letter-spacing: 4px;
		font-weight: bold;
		font-size: 4rem;
		text-align: center;
	}
	.bottom-text{
		color: var(--white);
		margin-top: -25px;
	}
	
	div h1{
		display: flex;
		align-items: center;
	}
	span{
		padding: 10px;
		color: var(--myRed);
		
	}

@media screen and (max-width: 900px) {
	.heading{
		font-size: 2rem;
	}
	
	}
	

</style>

