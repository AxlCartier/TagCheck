

<style>

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

</style>

<!--Below this goes for the button in HTML-->

<a href={link}>
    <button id="button" aria-label="button">
    <p>{title}</p>

    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path fill="none" d="M0 0h24v24H0z"></path><path d="M16.1716 10.9999L10.8076 5.63589L12.2218 4.22168L20 11.9999L12.2218 19.778L10.8076 18.3638L16.1716 12.9999H4V10.9999H16.1716Z"></path></svg>
</button>
</a>
<script>
    let { title, link } = $props();
</script>
<!--Above this goes for the button in HTML-->

