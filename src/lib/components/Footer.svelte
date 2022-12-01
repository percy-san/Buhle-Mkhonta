<script type="text/javascript">
	import Socials from '$lib/components/Socials.svelte'
	
</script>

<footer>
	<div class="top">
		<div class="logo">
			<img src="../images/Buhle.png">
		</div>
		<div class="location">
			<h2>Location</h2>
			<p class="home"><i class='bx bx-map'></i>Eswatini,Mbabane</p>
			
		</div>
		<div class="contact">
			<h2>Contact</h2>
			<p class="email"><i class='bx bx-envelope'></i>buhlebethumkhonta@gmail.com</p>

			
		</div>
		<div class="socials">
			<h2>Follow</h2>
			<Socials />
			
		</div>
	</div>
	<div class="bottom">
		<p class="attribution">Designed and Developed By <span>Buhle Mkhonta</span></p>
	</div>
	

</footer>

<style type="text/css">
	footer{
		position: relative;
		padding: 20px 20px 1px 20px;
	}
	.top{
		display: flex;
		align-items: center;
		justify-content: space-between;
	}

	.top .logo img{
		width: 6rem;
		border-radius: 15px;
	}
	.bottom img{
		display: none;
	}
	h2{
		color: white;
		font-size: 20px;
		font-weight: bold;
		letter-spacing: 2px;
		text-transform: uppercase;
		border-bottom: 3px solid var(--gray);
		padding-bottom: 5px;

	}
	i{
		margin-right: 5px;

	}
	.home,.email{
		display: flex;
		align-items: center;
		font-size: 18px;

	}

	.attribution{
		text-align: center;
		color: white;
		font-size: 18px;
	}
	.attribution span{
		color: var(--myRed);
	}
		
	
	
	@media screen and (max-width: 900px) {
		.top{
			display: none;
		}
		

		
		
		
	}
	
</style>