<script type="text/javascript">
	export let projectName = ""
	export let image = ""
	export let link =""
	
</script>

<div class="container">
    <div class="uk-card uk-card-default">
        <div class="uk-card-media-top ">
            <div class="image uk-height-medium uk-flex uk-flex-bottom uk-flex-middle uk-background-cover uk-light" data-src={image} uk-img>
			</div>
        </div>
        <div class="overlay">
    <div class="info">
    	<p class="project-name">{projectName}</p>
    	<a href={link} target="_blank"><button class="visit">VISIT SITE</button></a>

    </div>
  </div>

        
    </div>
</div>
 



<style type="text/css">
	.container{
		position: relative;
		transition: 0.5s ease;
	}
	.uk-card{
		cursor: pointer;
	}

	.overlay {
		position: absolute;
		bottom:0;
		left: 100%;
		right: 0;
		background-color: black;
		overflow: hidden;
		width: 0;
		height: 100%;
		transition: 0.4s ease-in-out;

	}



	.container:hover .overlay {
	  	opacity: 0.9;
	  	width: 100%;
  		left: 0;
	}

	.info{
  		position: absolute;
  		top: 50%;
  		left: 50%;
  		text-align: center;
  		-webkit-transform: translate(-50%, -50%);
  		-ms-transform: translate(-50%, -50%);
  		transform: translate(-50%, -50%);
  		
  		color: var(--white);
	}
	.project-name{
		font-size: 25px;
		color: white;
	}
	
	.visit{
		cursor: pointer;
		color: white;
		background: var(--myRed);
		border: none;
		padding: 5px;
		width: 8rem;
	}
	.visit:hover{
		background: var(--hoverRed);

	}


	
	


	

	
	
</style>