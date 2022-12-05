<script type="text/javascript">
	export let icon = ""
	export let serviceText = ""
	export let serviceDesc = ""
</script>

<div>
	<div class="card" >
		<i class={`${icon}`}  ></i>
		<p class="header">{serviceText}.</p>
		<p class="desc">{serviceDesc}</p>

	</div>
</div>

<style type="text/css">
	.card{
		position: relative;
		height: 300px;
		width: 300px;
		padding: 10px;
		text-align: center;
		-webkit-box-shadow: 6px 14px 17px 3px rgba(0,0,0,0.38); 
				box-shadow: 6px 14px 17px 3px rgba(0,0,0,0.38);
		transition: var(--trans);
			

	}
	i{
		display: block;
		margin: 0 auto;
		width: 50%;
		font-size: 90px;
		color: var(--myRed);
		
	}
	.header{
		color: white;
		font-size: 25px;
		letter-spacing: 1px;
		width: 100%;
	}
	
	


	

</style>
