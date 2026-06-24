<style>

.container {  

  display: grid;
  grid-template-columns: 1.3fr 0.9fr 0.8fr;
  grid-template-rows: 3fr repeat(7, 1.5fr);
  grid-gap: 1px 2px ;
  
  grid-auto-flow: row;
  background-color: none;
  grid-template-areas:
    ". . ."
    ". . ."
    ". . ."
    ". . ."
    ". . ."
    ". . ."
    ". . ."
    ". . .";

    margin-left: 5%;
    overflow: hidden;
    
}

.container h1 {
    padding: 20px 10px;
    width: max-content;
    display: flex;
    align-items: center;

    color: var(--c);
}

.container svg {
    padding: 20px 10px;
    width: max-content;
    height: max-content;


    display: flex;
    justify-self: center;
    align-self: center;

    fill: var(--c);

    display: flex;
    justify-content: center;
    align-items: center;
}


/*Created from https://grid.layoutit.com by LenioLabs_ */

/*-------------------- the grid ------------------*/

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

/*-------------------- the rest ------------------*/


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

@media (max-width: 800px) {
    
    h3 {
        margin-left: 0%;
    }
    
    section {
        gap: 0px;
    }

         .container {
        margin-left: 0%;
    }

    .container h1 {
        font-size: 17px;
    }




}



 


</style>

<!--Below this goes for the comparator in HTML-->

<section id={id}>
    <h3>{title}</h3>
    
    
    <!--The blue button-->
        <button id="button" aria-label="button">
           <p>Show More</p>

           <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path fill="none" d="M0 0h24v24H0z"></path><path d="M16.1716 10.9999L10.8076 5.63589L12.2218 4.22168L20 11.9999L12.2218 19.778L10.8076 18.3638L16.1716 12.9999H4V10.9999h16.1716Z"></path></svg>
        </button>

</section>


        

    <!--The blue button-->
    <!--Used as a prop later hopefully (the link to the button)-->
   
<div class="container">

    
    <b><h1>Products</h1></b> <!-- The question / divider -->
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" height="60px" width="60px" fill="currentColor"><path fill="none" d="M0 0h24v24H0z"></path><path d="M12 2C16.9706 2 21 6.02944 21 11V18.5C21 20.433 19.433 22 17.5 22C16.3001 22 15.2413 21.3962 14.6107 20.476C14.0976 21.3857 13.1205 22 12 22C10.8795 22 9.9024 21.3857 9.38728 20.4754C8.75869 21.3962 7.69985 22 6.5 22C4.63144 22 3.10487 20.5357 3.00518 18.692L3 18.5V11C3 6.02944 7.02944 2 12 2ZM12 4C8.21455 4 5.1309 7.00478 5.00406 10.7593L5 11L4.99927 18.4461L5.00226 18.584C5.04504 19.3751 5.70251 20 6.5 20C6.95179 20 7.36652 19.8007 7.64704 19.4648L7.73545 19.3478C8.57033 18.1248 10.3985 18.2016 11.1279 19.4904C11.3053 19.8038 11.6345 20 12 20C12.3651 20 12.6933 19.8044 12.8687 19.4934C13.5692 18.2516 15.2898 18.1317 16.1636 19.2151L16.2606 19.3455C16.5401 19.7534 16.9976 20 17.5 20C18.2797 20 18.9204 19.4051 18.9931 18.6445L19 18.5V11C19 7.13401 15.866 4 12 4ZM16 13C16 15.2091 14.2091 17 12 17C9.8578 17 8.10892 15.316 8.0049 13.1996L8 13H10C10 14.1046 10.8954 15 12 15C13.1046 15 14 14.1046 14 13H16ZM12 7C13.1046 7 14 7.89543 14 9C14 10.1046 13.1046 11 12 11C10.8954 11 10 10.1046 10 9C10 7.89543 10.8954 7 12 7Z"></path></svg> 
    <!-- The first -->
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" height="60px" width="60px" fill="currentColor"><path fill="none" d="M0 0h24v24H0z"></path><path d="M21.1634 10.9711C21.5132 10.8204 21.9579 11.0073 21.9811 11.3875C22.1494 14.1467 21.1794 16.9625 19.071 19.0709C15.1657 22.976 8.83405 22.9761 4.92886 19.0709C1.02367 15.1657 1.02377 8.83405 4.92885 4.9288C7.03704 2.82061 9.8525 1.85015 12.6115 2.01806C12.9916 2.04119 13.1787 2.48598 13.028 2.83576C12.4774 4.11367 12.7239 5.65275 13.7677 6.69657C14.3307 7.25963 15.038 7.58971 15.7706 7.68848C16.0483 7.72594 16.2738 7.95144 16.3113 8.2292C16.4101 8.96178 16.7402 9.66905 17.3032 10.2321C18.347 11.2759 19.8857 11.5218 21.1634 10.9711ZM19.7845 13.8397C19.8558 13.5362 19.6123 13.2603 19.3017 13.2337C18.0569 13.1271 16.8417 12.599 15.889 11.6463C15.3166 11.0739 14.8979 10.4061 14.6309 9.69455C14.5744 9.54422 14.4556 9.42534 14.3052 9.36892C13.5936 9.10186 12.9259 8.68322 12.3535 8.11078C11.4005 7.15778 10.8715 5.94208 10.7648 4.69683C10.7381 4.38618 10.4621 4.14264 10.1586 4.2141C8.76039 4.54327 7.43341 5.25267 6.34306 6.34301C3.21903 9.46721 3.21893 14.5326 6.34307 17.6567C9.46721 20.7809 14.5326 20.7808 17.6568 17.6567C18.7474 16.566 19.4557 15.2384 19.7845 13.8397ZM9.8786 14.1212C10.4644 14.707 10.4644 15.6567 9.8786 16.2425C9.29281 16.8283 8.34307 16.8283 7.75728 16.2425C7.17149 15.6567 7.17149 14.707 7.75728 14.1212C8.34306 13.5354 9.29281 13.5354 9.8786 14.1212ZM10.2321 8.11078C10.8179 8.69657 10.8179 9.64631 10.2321 10.2321C9.64636 10.8179 8.69661 10.8179 8.11083 10.2321C7.52504 9.64631 7.52504 8.69656 8.11083 8.11078C8.69661 7.52499 9.64636 7.52499 10.2321 8.11078ZM15.889 13.7676C16.4748 14.3534 16.4748 15.3032 15.889 15.889C15.3032 16.4747 14.3535 16.4747 13.7677 15.889C13.1819 15.3032 13.1819 14.3534 13.7677 13.7676C14.3535 13.1818 15.3032 13.1818 15.889 13.7676Z"></path></svg>
    <!-- The second -->
    <h1>hello world</h1> <!-- The question / divider -->
    <h1>hello world</h1> <!-- The first -->
    <h1>hello world</h1> <!-- The second -->
    <h1>hello world</h1> <!-- The question / divider -->
    <h1>hello world</h1> <!-- The first -->
    <h1>hello world</h1> <!-- The second -->
    <h1>hello world</h1> <!-- The question / divider -->
    <h1>hello world</h1> <!-- The first -->
    <h1>hello world</h1> <!-- The second -->
    <h1>hello world</h1> <!-- The question / divider -->
    <h1>hello world</h1> <!-- The first -->
    <h1>hello world</h1> <!-- The second -->
    <h1>hello world</h1> <!-- The question / divider -->
    <h1>hello world</h1> <!-- The first -->
    <h1>hello world</h1> <!-- The second -->
    <h1>hello world</h1> <!-- The question / divider -->
    <h1>hello world</h1> <!-- The first -->
    <h1>hello world</h1> <!-- The second -->
    <h1>hello world</h1> <!-- The question / divider -->
    <h1>hello world</h1> <!-- The first -->
    <h1>hello world</h1> <!-- The second -->
    <h1>hello world</h1> <!-- The question / divider -->
    <h1>hello world</h1> <!-- The first -->
    <h1>hello world</h1> <!-- The second --> 
    <h1>hello world</h1> <!-- The question / divider -->
    <h1>hello world</h1> <!-- The first -->
    <h1>hello world</h1> <!-- The second -->
    <h1>hello world</h1> <!-- The question / divider -->
    <h1>hello world</h1> <!-- The first -->
    <h1>hello world</h1> <!-- The second -->
 


</div>



<!--Above this goes for the comparator in HTML-->

<script>
let { title, id } = $props();
</script>

