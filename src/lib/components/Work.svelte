<script type="text/javascript">
	import Section from '$lib/shared/Section.svelte'
	import WorkCard from '$lib/shared/workCards.svelte'

	let projects = [
    {name:"Project", description:"THIS IS THE DESCTIPTION", link:"link",image:"../images/Software-Developer.svg"},
    {name:"Project", description:"THIS IS THE DESCTIPTION", link:"link",image:"../images/Software-Developer.svg"},
    {name:"Project", description:"THIS IS THE DESCTIPTION", link:"link",image:"../images/Software-Developer.svg"},
    {name:"Project", description:"THIS IS THE DESCTIPTION", link:"link",image:"../images/Software-Developer.svg"}
  ]
	
</script>


<main>
<Section heading ={"Work"} number={"03"}/>
<div class="work-section uk-grid-medium uk-child-width-expand@s uk-text-center" uk-grid>
	{#each projects as project}
		<WorkCard projectName ={project.name} description = {project.description} image={project.image}/>
	{/each}

</div>

	
</main>

<style type="text/css">
	
</style>