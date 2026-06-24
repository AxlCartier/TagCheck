<style>
    #button {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    margin: 0px 0px;

    height: 50px; 
    width: 230px;
    gap: 10px;
    padding: 5px 2px;
    border-radius: 10px;

    
    background-color: var(--primary); 
    border: 1px solid var(--bg); 
}

#button p {
    font-family: "Inter";
    font-weight: 500;
    font-size: 20px;

    padding: 0px 5px;
    color: white;
}

#button svg {
    margin: 0px 5px;
    height: 30px;
    width: 30px;
    fill: white;
}

#button:hover {
    opacity: 0.8;
    transition: 0.5s;
}

@media (max-width: 700px) {
        #button {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    margin: 0px 0px;

    height: fit-content; 
    width: 100px;
  
    padding: 5px 2px;
    border-radius: 10px;

    
    background-color: var(--primary); 
    border: 1px solid var(--bg); 
}

#button p {
    font-family: "Inter";
    font-size: 15px;

    padding: 0px 0px;
    color: white;
}

#button svg {
    margin: 0px 5px;
    height: 20px;
    width: 20px;
    fill: white;
}

#button:hover {
    opacity: 0.8;
    transition: 0.5s;
 }
}


</style>

<!--Below this goes for the button in HTML-->

<button id="button">
    <p>View More</p>

    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path fill="none" d="M0 0h24v24H0z"></path><path d="M18.031 16.6168L22.3137 20.8995L20.8995 22.3137L16.6168 18.031C15.0769 19.263 13.124 20 11 20C6.032 20 2 15.968 2 11C2 6.032 6.032 2 11 2C15.968 2 20 6.032 20 11C20 13.124 19.263 15.0769 18.031 16.6168ZM16.0247 15.8748C17.2475 14.6146 18 12.8956 18 11C18 7.1325 14.8675 4 11 4C7.1325 4 4 7.1325 4 11C4 14.8675 7.1325 18 11 18C12.8956 18 14.6146 17.2475 15.8748 16.0247L16.0247 15.8748ZM12.1779 7.17624C11.4834 7.48982 11 8.18846 11 9C11 10.1046 11.8954 11 13 11C13.8115 11 14.5102 10.5166 14.8238 9.82212C14.9383 10.1945 15 10.59 15 11C15 13.2091 13.2091 15 11 15C8.79086 15 7 13.2091 7 11C7 8.79086 8.79086 7 11 7C11.41 7 11.8055 7.06167 12.1779 7.17624Z"></path></svg>
</button>


<!--Above this goes for the button in HTML-->