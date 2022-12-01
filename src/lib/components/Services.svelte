<script type="text/javascript">
	import Section from '$lib/shared/Section.svelte'
	import Card from '$lib/shared/Cards.svelte'

	let desc = "Lorem ipsum is placeholder text commonly used in the graphic, print, and publishing industries for previewing layouts and visual mockups."
	
</script>

<main>
	<Section  topHeader={"What I Offer"} heading ={"Services"} number={"01"}/>
	<div class="services-section" >
		<Card icon={'bx bx-laptop'} serviceText = {"WEB DEVELOPMENT"} serviceDesc ={desc}/>
		<Card icon={'bx bx-mobile-alt'} serviceText = {"APP DEVELOPMENT"} serviceDesc ={desc}/>
		<Card icon={'bx bx-scatter-chart'} serviceText = {"DATA ANALYSIS"} serviceDesc ={desc}/>

	</div>
	
	


	
</main>


<style>
	.services-section{
		display: flex;
		justify-content: space-between;
		align-items: center;
		width: 100%;
		padding: 20px 5px 10px 0;
	}
	@media screen and (max-width: 900px) {
		.services-section{
			flex-direction: column;
			gap: 50px;
		}
		
		

		
	}
	
	
	
	
</style>