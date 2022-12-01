<script type="text/javascript">
	import Socials from '$lib/components/socials.svelte'
	
</script>

<main>
	<div class="hero" >
		<div class="info">
			<p class="name">Hello, i'm BUHLE MKHONTA</p>
			<div class="summary">
				<p>Professional Software Engineer & Web developer</p>
			</div>
			<a class="btn-link" href="../Resume.pdf" download><button class="cv-btn"><i class='bx bx-download'></i></button>DOWNLOAD CV</a>	
		</div>
	</div>

	<div class="hero-image">
		<img src="../images/Me.svg" alt="hero-image">
	</div>
	
</main>

<style type="text/css">
	main{
		display: flex;
		align-items: center;
		
	}
	.hero{
		position: relative;
		padding: 10px;


		
	}
	.hero-image{
		height: 100%;
		padding: 5px;

		
	}
	.info{
		color: white;
		

	}
	.name{
		font-size: 35px;
		color: #5B5B5B;
		font-size: 20px;
		font-weight: bold;
		letter-spacing: 1px;
	}
	.summary p{
		font-size: 50px;
		width: 100%;
	}
	
	

	.cv-btn{
		background: var(--myRed);
		color: white;
		font-size: 30px;
		border-radius: 5px;
		height: 5rem;
		width: 5rem;
		padding: 10px;
		margin-right: 5px;
		letter-spacing: 1px;
		cursor: pointer;
		transition: var(--trans);
	}

	.btn-link{
		color:#5B5B5B;

	}
	.btn-link:hover{
		text-decoration: none;
		color: var(--hoverRed);

	}
	
	

	@media screen and (max-width: 900px) {
		main{
			display: flex;
			flex-wrap: wrap;
				
		}
		
		
		

		
	}
	
	
	
	
	


	

</style>