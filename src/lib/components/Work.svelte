<script type="text/javascript">
	import Section from '$lib/shared/Section.svelte'
	import WorkCard from '$lib/shared/workCards.svelte'


	
</script>


<main>
<Section heading ={"Work"} number={"03"} bottomText={"Some stuff I have done"}/>

<div class="work-section">
	<div class="project-1" uk-scrollspy="cls: uk-animation-fade; delay: 500; repeat: false">
		<WorkCard projectName ={"Dreamcatcher Album preview"} image={"../images/dreamcatcher-album.jpeg"} link ={'https://album-page.vercel.app/'}/>
		
	</div>
		
	<div class="project-2" uk-scrollspy="cls: uk-animation-fade; delay: 600; repeat: false">
		<WorkCard projectName ={"Tip Calulator"} image={"../images/tip-calculator.jpeg"} link={'https://tip-calculator-app-nu-self.vercel.app/'}/>
			
	</div>

	<div class="project-3" uk-scrollspy="cls: uk-animation-fade; delay: 700; repeat: false">
		<WorkCard projectName ={"Crowd Fund Challange"} image={"../images/crowdfunding.jpeg"} link={'https://crowdfund-challange.vercel.app/'}/>
			
	</div>

	<div class="project-4" uk-scrollspy="cls: uk-animation-fade; delay: 800; repeat: false">
		<WorkCard projectName ={"Blog"} image={"../images/Blog.jpeg"} link={'https://buhlebethu-mkhonta.netlify.app/'}/>
			
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