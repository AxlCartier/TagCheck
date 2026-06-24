<svelte:head>
    <title>TagCheck</title>  <!--Dynamic title?-->
</svelte:head>

<!--Hero section-->
<HeroSection/> 
<!--Hero section-->


<!--Card Carousel/Section-->
<CardCarousel 
title={"Gaming"}  
id={"gaming"}
show_more_link={"https://github.com/AxlCartier"}/>

<CardCarousel 
title={"Electronics"} 
id={"electronics"}
show_more_link={"https://github.com/AxlCartier"}/>

<CardCarousel 
title={"Consoles"} 
id={"consoles"}
show_more_link={"https://github.com/AxlCartier"}/>

<CardCarousel 
title={"Computers"} 
id={"computers"}
show_more_link={"https://github.com/AxlCartier"}/>

<CardCarousel 
title={"Hardware"} 
id={"hardware"}
show_more_link={"https://github.com/AxlCartier"}/>

<CardCarousel 
title={"Search"} 
id={"search"}
show_more_link={"https://github.com/AxlCartier"}/>

<Comparator 
title={"Compare"} 
id={"compare"}
show_more_link={"https://github.com/AxlCartier"}/>


<!--Card Carousel/Section-->







<script>
    import '/static/app.css'
    import HeroSection from '../components/HeroSection.svelte';
    import CardCarousel from '../components/CardCarousel.svelte';
    import Comparator from '../components/Comparator.svelte';
</script>





<!--Dynamic routing...-->

<!--Don't forget that most of these (mini)components should
also be props-->




<!--Assuming you've created a slug, then create an
error page-->

<!--Read more here: https://svelte.dev/docs/kit/errors     -->

<!--
<script>
    let { data } = $props();
</script>



{#each products as product}
    <a href={`/${product.slug}`}>
                {product.title}
    </a>
{/each}




-->