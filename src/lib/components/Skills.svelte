<script type="text/javascript">
	import Section from '$lib/shared/Section.svelte'
	
</script>


<main>
<Section  heading ={"Skills"} number={"02"} bottomText={"What I use"}/>
<div class="slider" uk-slider="autoplay: true; autoplay-interval:1800; pause-on-hover: true; center:true">
    <div class="uk-position-relative">

        <div class="uk-slider-container uk-light" uk-scrollspy="cls: uk-animation-slide-bottom-small; delay: 200; repeat: true">
            <ul class="uk-slider-items uk-child-width-1-2 uk-child-width-1-3@s uk-child-width-1-4@m">
            	 
                <li>
                    <img src="../images/svelte-icon.svg" alt="" uk-tooltip="title:Svelt; pos: bottom">
                </li>
               
                <li>
                    <img src="../images/javascript-icon.svg"  alt="" uk-tooltip="title: JavaScript; pos: bottom">
                </li>
                <li>
                    <img src="../images/tailwind-icon.svg"  alt="" uk-tooltip="title: Tailwind CSS; pos: bottom">
                </li>
                <li>
                    <img src="../images/sass-icon.svg"  alt="" uk-tooltip="title: SASS; pos: bottom">
                </li>
                <li>
                    <img src="../images/uikit-icon.svg"  alt="" uk-tooltip="title: UIkit; pos: bottom">
                </li>
                <li>
                    <img src="../images/firebase-icon.svg"  alt="" uk-tooltip="title: UIkit; pos: bottom">
                </li>
                <li>
                    <img src="../images/python-icon.svg"  alt="" uk-tooltip="title: Python; pos: bottom">
                </li>
               
                
                
            </ul>
        </div>

        

    </div>

    <ul class="uk-slider-nav uk-dotnav uk-flex-center uk-margin"></ul>

</div>

	
</main>

<style type="text/css">
	.slider{
		display: block;
		margin: 0 auto;
		width:90%;
		padding-top: 20px;

	}
	.uk-slider-items{
		display: flex;
		align-items: center;
	}
	.uk-slider-items li{
		padding-bottom: 10px;
	}
    li img{
        width: 150px;
    }

    @media screen and (max-width: 900px) {
    li img{
        width: 90px;
        
    }
    
    }
	
	
</style>