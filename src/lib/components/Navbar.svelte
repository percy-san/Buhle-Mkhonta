<script type="text/javascript">
	
</script>

<nav>
	<div class="left">
		<a href="/" class="logo"><img src="../images/Buhle.png" alt="logo"></a>
	</div>
	<div class="right">
		<div class="full-nav">
			<ul>
				<li><a href="#services">Services</a></li>
				  
				<li><a href="#skills">Skills</a></li>
				        
				<li><a href="#work">Work</a></li>
				        
				<li><a href="#contact">Contact</a></li>

				<li><a href="https://buhlebethu-mkhonta.netlify.app/" target="_blank">Blog</a></li>

			</ul>
			

		</div>
		<div class="resp-nav">
			<i class='bx bx-menu-alt-right '  uk-toggle="target: #offcanvas-flip"></i>
			<div id="offcanvas-flip" uk-offcanvas="flip: true">
				<div class="uk-offcanvas-bar uk-flex uk-flex-column">
					<i class='bx bx-menu-alt-left uk-offcanvas-close' ></i>
				    <ul class="uk-nav uk-nav-primary ">
				    	<li><a href="#services" >Services</a></li>
				  		<hr>
						<li><a href="#skills">Skills</a></li>
				  		<hr>
						<li><a href="#work">Work</a></li>
				        <hr>
						<li><a href="#contact">Contact</a></li> 
				        <hr>
						<li><a href="https://buhlebethu-mkhonta.netlify.app/" target="_blank">Blog</a></li>

				        
				    </ul>
		    	</div>
				</div>
			
		</div>
		
	</div>
</nav>

<style type="text/css">
	a{
		color: white;
		text-decoration: none;
		font-size: 20px;
		font-weight: bold;
		letter-spacing: 1px;
	}
	nav{
		display: flex;
		align-items: baseline;
		justify-content: space-between;
		padding: 20px 20px 0 20px;
		
		
	}
	.logo img{
		width:100px;
		border-radius: 15px;
		
	}
	.bx-menu-alt-right{
		font-size:3rem;
		color: white;
	}
	
	.right {
		display: flex;
		align-items: center;

	}

	.full-nav ul{
		display: flex;
		align-items: center;
		justify-content: space-between;

	}
	.full-nav ul li {
		margin-right: 15px;
		list-style: none;
	}
	.resp-nav{
		display: none;

	}
	.resp-nav ul li a{
		list-style: none;
		color: white;
		font-size: 35px;
		transition: var(--trans);
	}
	.uk-offcanvas-close{
		color: white;
		font-size: 35px;
		transition: var(--trans);
	}
	.uk-nav{
		display: block;
		margin: 5rem auto;


	}
	ul li a{
		transition: var(--trans);
	}
	ul li a:hover,.uk-offcanvas-close:hover,.bx-menu-alt-right{
		color: var(--myRed);
	}
	.bx-menu-alt-right:hover{
		color:#FF6D6D ;
	}


	@media only screen and (max-width: 900px) {
		.full-nav{
			display: none;
		}
		.resp-nav{
			display: block;
			z-index: 5;
		}
		.logo{font-size: 20px;}

		}
		.bx-menu-alt-right{
			font-size: 2rem;
		}

	
</style>