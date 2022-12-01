<script type="text/javascript">
	export let projectName = ""
	export let description = ""
	export let image = ""
	
</script>

<div class="uk-card  uk-card-body uk-width-1-2@m">
	<div class="uk-text-center">
        <div class="uk-inline-clip uk-transition-toggle" tabindex="0">
            <img src={image} alt="">
            <div class="uk-transition-fade uk-position-cover uk-overlay uk-overlay-primary uk-flex uk-flex-center uk-flex-middle">
                <p class="uk-h4 uk-margin-remove">Fade</p>

            </div>
        </div>
    </div>
    
</div>

<style type="text/css">
	.uk-card{
		
		border-radius: 20px;
		background-size: cover;
		background-repeat: no-repeat;


	}
	
</style>