<style>

#card {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    padding: 10px 25px;

    height: max-content; 
    width: 250px;
    gap: 10px;
    border-radius: 10px;

    
    background-color: white;
    border: 5px solid black;
}

#card p {
    font-family: "Inter";
    font-weight: 500;
    font-size: 30px;

    padding: 0px 5px;
    color: black;
}

#card svg {
    margin: 0px 5px;
    margin: 20px 0px;
    fill: black;
}


#flex {
    display: flex;
    flex-direction: row;
    justify-self: center;
    align-self: center;
}

#flex p {
    margin: 15px 0px;
}

#flex p::first-line {
   text-decoration: underline;
}

@media (max-width: 700px) {
    #card {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    padding: 10px 25px;

    height: fit-content; 
    width: 150px;
    gap: 10px;
    border-radius: 10px;

    background-color: white;
    border: 5px solid black;
}

#card p {
    font-family: "Inter";
    font-weight: 500;
    font-size: 20px;

    padding: 0px 5px;
    color: black;
}


#flex p {
    margin: 25px 0px;
}


}


</style>

<!--Below this goes for the button in HTML-->
<section id="card">
    <svg id="photo" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" height="50px" width="50px"  fill="currentColor"><path fill="none" d="M0 0h24v24H0z"></path><path d="M2.9918 21C2.44405 21 2 20.5551 2 20.0066V3.9934C2 3.44476 2.45531 3 2.9918 3H21.0082C21.556 3 22 3.44495 22 3.9934V20.0066C22 20.5552 21.5447 21 21.0082 21H2.9918ZM20 15V5H4V19L14 9L20 15ZM20 17.8284L14 11.8284L6.82843 19H20V17.8284ZM8 11C6.89543 11 6 10.1046 6 9C6 7.89543 6.89543 7 8 7C9.10457 7 10 7.89543 10 9C10 10.1046 9.10457 11 8 11Z"></path></svg>
     <!--Prop later, hopefully (the SVG)-->

    <div class="line">
    <p>Name Of Product  <!--Prop later, hopefully-->
        <b>$49.99</b></p>  <!--Prop later, hopefully-->
    </div>

    <div id="flex">
     <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" height="40px"  width="40px" fill="rgba(255,255,255,1)"><path fill="none" d="M0 0h24v24H0z"></path><path d="M12.0006 18.26L4.94715 22.2082L6.52248 14.2799L0.587891 8.7918L8.61493 7.84006L12.0006 0.5L15.3862 7.84006L23.4132 8.7918L17.4787 14.2799L19.054 22.2082L12.0006 18.26ZM12.0006 15.968L16.2473 18.3451L15.2988 13.5717L18.8719 10.2674L14.039 9.69434L12.0006 5.27502L9.96214 9.69434L5.12921 10.2674L8.70231 13.5717L7.75383 18.3451L12.0006 15.968Z"></path></svg>  
     <p><b>6.7/10</b></p>  <!--Prop later, hopefully-->
    </div>

    <ViewMoreButton/>
    
</section>
    
    
<script>
    import ViewMoreButton from "./ViewMoreButton.svelte";
</script>

<!--Above this goes for the button in HTML-->