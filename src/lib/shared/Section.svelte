<script type="text/javascript">
	export let heading = ""
	export let number
	
	
	
</script>

<main>
	<div>
		<h1 class="heading"><span>{number}</span>{heading}</h1>
		
		
	</div>

</main>

<style type="text/css">
	.heading{
		text-transform: uppercase;
		color: white;
		letter-spacing: 4px;
		font-weight: bold;
		font-size: 3rem;
		padding-bottom: 5px;
		margin-top:-15px;
		max-width: 50%;
	}
	
	div h1{
		display: flex;
		align-items: center;
	}
	span{
		padding: 10px;
		font-size: 25px;
		color: var(--myRed);
		margin-right: 10px;
	}

@media screen and (max-width: 900px) {
	.heading{
		font-size: 3rem;
	}
	
	}
	

</style>

