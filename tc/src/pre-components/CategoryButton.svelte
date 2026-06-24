<style>

#button {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;

    padding: 8px 16px;

    max-width: fit-content;

    border: 1px solid var(--c); 
    border-radius: 15px;
    margin-bottom: 10px;

    background-color: var(--bg);
}

#button p {
    font-family: "Inter";
    font-size: 20px;
    padding: 0px 5px;
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



</style>


<!--Below this goes for the button in HTML-->
    <a href={link} aria-label="Category">
        <button id="button">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path fill="none" d="M0 0h24v24H0z"></path><path d={svg}></path></svg>  
    <!--Copy everything from the last "d"-->
          <p>{category}</p>
        </button>
    </a>  
<script>
    let {svg, category, link } = $props();
</script>

<!--Above this goes for the button in HTML-->