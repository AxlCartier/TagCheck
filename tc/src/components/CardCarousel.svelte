<style>

/*-------------- the blue button---------------------*/

#button {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;

    height: 50px; 
    width: 160px;

    
    background-color: var(--primary);
    border: 1px solid var(--c);
    border-radius: 15px;
}

#button p {
    font-family: "Inter";
    font-size: 18.5px;
    padding: 5px 5px;
    color: var(--c);
}

#button svg {
    margin: 0px 5px;
    height: 30px;
    width: 30px;
    fill: var(--c);
}

#button:hover {
    opacity: 0.8;
    transition: 0.5s;
}

@media (max-width: 560px) {
    #button {
      height: 40px; 
      width: 130px;
    }

    #button p {
        font-size: 15px;
    }

    #button svg {
        height: 15px;
        width: 15px;
        fill: var(--c);
    }
}

/*-------------- the blue button---------------------*/


/*----------------The rest-------------------*/

section {
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;

    padding: 30px 10px;

    gap: 100px;
    
}



h3 {
    font-weight: 600;
    margin-left: 46%;
}

h3::first-line {
    text-decoration: underline;
}

.cards {
    padding: 30px 10px;
    height: fit-content;

    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    align-items: center;
    overflow-x: scroll;
  
    gap: 20px;
}

.cards::-webkit-scrollbar {
    display: none;
}


@media (max-width: 800px) {
    
    h3 {
        margin-left: 10%;
    }
    
    section {
        gap: 0px;
    }
}
 


</style>

<!--Below this goes for the card carousel in HTML-->

<section id={id}>
    <h3>{title}</h3>
    
    
    <!--The blue button-->
    <a href={show_more_link} aria-label="link to go to the full sections">
        <button id="button" aria-label="button">
           <p>Show More</p>

           <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path fill="none" d="M0 0h24v24H0z"></path><path d="M16.1716 10.9999L10.8076 5.63589L12.2218 4.22168L20 11.9999L12.2218 19.778L10.8076 18.3638L16.1716 12.9999H4V10.9999H16.1716Z"></path></svg>
        </button>
    </a>
        

</section>


    <!--The blue button-->
    
    <!--Used as a prop later hopefully (the link to the button)-->


    <div class="cards">
        <Card/>
        <Card/>
        <Card/>
        <Card/>
        <Card/>
        <Card/>
        <Card/>
        <Card/>
        <Card/>
        <Card/>
        <Card/>
        <Card/>
        <Card/>
        <Card/>
        <Card/>
        <Card/>
    </div>



<!--Above this goes for the card carousel in HTML-->


<script>
import Card from "../pre-components/Card.svelte";
let { title, id, show_more_link } = $props();
</script>

<!--The blue button-->

