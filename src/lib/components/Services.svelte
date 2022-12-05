<script type="text/javascript">
	import Section from '$lib/shared/Section.svelte'
	import Card from '$lib/shared/Cards.svelte'

		
</script>

<main>
	<Section heading ={"Services"} number={"01"} bottomText={"Services I offer"}/>
	<div class="services-section" >

		<div uk-scrollspy="cls: uk-animation-fade; delay: 200; repeat: true">
			<Card icon={'bx bx-laptop'} serviceText = {"WEB DEVELOPMENT"} serviceDesc ={"Using Svelte, Tailwind,Uikit and firebase. I can create fully responsive websites for all your personal needs"}/>
		</div>	

		<div uk-scrollspy="cls: uk-animation-fade; delay: 250; repeat: true">
			<Card icon={'bx bx-brush'} serviceText = {"Web Design"} serviceDesc ={"Using Figma and Webflow, i can create designs that you will be satisfied with."}/>
		</div>

		<div uk-scrollspy="cls: uk-animation-fade; delay: 300; repeat: true">
			<Card icon={'bx bx-bot'} serviceText = {"ChatBot Creation"} serviceDesc ={"Using Services such as IBM Watson Assistant, i can create chatbots for ur business to handle customer queries."}/>
		</div>

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