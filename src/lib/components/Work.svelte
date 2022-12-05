<script type="text/javascript">
	import Section from '$lib/shared/Section.svelte'
	import WorkCard from '$lib/shared/workCards.svelte'


	
</script>


<main>
<Section heading ={"Work"} number={"03"} bottomText={"Some stuff I have done"}/>

<div class="work-section">
	<div class="project-1" uk-scrollspy="cls: uk-animation-slide-top; delay: 500; repeat: true">
		<WorkCard projectName ={"Dreamcatcher Album preview"} image={"../images/dreamcatcher-album.jpeg"} link ={'https://album-page.vercel.app/'}/>
		
	</div>
		
	<div class="project-2" uk-scrollspy="cls: uk-animation-slide-bottom; delay: 600; repeat: true">
		<WorkCard projectName ={"Tip Calulator"} image={"../images/tip-calculator.jpeg"} link={'https://tip-calculator-app-nu-self.vercel.app/'}/>
			
	</div>
		
	
		
	

</div>

	
</main>

<style type="text/css">
	.work-section{
		display: grid;
		grid-template-columns: 1fr 1fr 1fr;
		grid-template-rows: auto;
		grid-template-areas:"project-1 project-1 project-2"
							 ;
		gap: 20px;
		padding: 0 40px 0 40px;
	}
	.project-1{
		grid-area: project-1;
	}
	.project-2{
		grid-area: project-2;
	}
	


	@media screen and (max-width: 900px) {
		.work-section{
			display: flex;
			flex-direction: column;
		}

		

	
	}
	
</style>