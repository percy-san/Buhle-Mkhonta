<script type="text/javascript">
	import Section from '$lib/shared/Section.svelte'
	import Socials from '$lib/components/socials.svelte'
	
</script>

<Section heading ={"Contact"} number={"04"} bottomText={"Feel free to send me an email directly for questions.I would love to here from you."}/>
<main uk-scrollspy="cls: uk-animation-slide-bottom; delay: 200; repeat: true">
	

	<div class="info">
		<div class="area">
			<p class="header"><i class='bx bx-envelope' ></i>Email:</p>
			<p class="email">buhlebethumkhonta@gmail.com</p>

		</div>
		<div class="area">
			<p class="header"><i class='bx bx-map'></i>location:</p>
			<p class="location">Eswatini,Mbabane</p>

		</div>
		<div class="area">
			<p class="header">Follow:</p>
			<Socials />
		</div>
	</div>
</main>

<style type="text/css">
	main{
		display: block;
		margin: 50px auto;
		width: 90%;
		text-align: center;
	}
	

	.area{
		margin-bottom: 3rem;
	}
	.header{
		color:white;
		font-size: 25px;
		border-bottom: 1px solid var(--myRed);
		
	}
	.email,.location{
		color: var(--white);
		font-size: 20px;
	}
	i{
		margin-right: 5px;
	}
	

	

@media screen and (max-width: 900px) {
	

		
}
</style>