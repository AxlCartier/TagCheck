<style>
    section {
    display: flex;
    flex-wrap: wrap;
    /*padding: 8% 3%;*/

    width: 100%;
    /*border: 1px solid black;*/
    contain: content;
}

section .left {
    display: flex;
    flex-direction: column;



    padding: 0px 20px;
    margin-bottom: 1%;
    width: 50%;
    font-size: clamp(5px, 20px, 2em);

    /*border: 1px solid black;*/

}

section .left #svg {
    padding: 50px 10px;


    /*border: 1px solid black;*/
    fill: var(--c);


    display: flex;
    flex-wrap: wrap;
    justify-self: center;
    align-self: center;
}

.flex {
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    color: var(--c);

    margin: 5% 0px;
    /*border: 1px solid black;*/
}

#flex {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;

    justify-content: flex-start;
    align-items: center;
    margin-bottom: 20px;
}

#flex svg {
    fill: var(--c);
    height: 30px;
    height: 30px;
}



/*---------------- right side --------------------*/


section .right{
    display: flex;
    flex-direction: column;

    padding: 0px 20px;
    margin-top: 7%;
    margin-bottom: 1%;
    width: 50%;

        color: var(--c);


    justify-self: center;
    align-items: center;
    font-size: clamp(5px, 20px, 2em);


    /*border: 1px solid black;*/
}


#right{
    display: flex;
    flex-direction: row;
    justify-self: center;
    align-self: center;

    font-size: var(--h3-text);
    color: var(--c);
    font-weight: 700;

    padding: 10px 16px;

    
}

#right svg {
    fill: black;
    justify-self: center;
    align-self: center;
    margin-inline-start: 15px;
}

h3::first-line {
    text-decoration: underline;
}


@media (max-width: 650px) {
    section {
        flex-direction: column;
    }

    section .left, section .right {
        width: 100%;
    }


}
</style>


<!--Below this goes for the card thingy in HTML-->
<section>
    <button class="absolute top-0 left-0 pt-10 pl-10 border-opacity-0" aria-label="button">
        <a href="/" aria-label="arrow to go back to the home page">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="60" height="60" fill="currentColor"><path fill="none" d="M0 0h24v24H0z"></path><path d="M12 13V20L4 12L12 4V11H20V13H12Z"></path></svg>
        </a>
    </button>


<div class="left">
        <svg id="svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path fill="none" d="M0 0h24v24H0z"></path><path d="M12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22ZM12 20C16.4183 20 20 16.4183 20 12C20 7.58172 16.4183 4 12 4C7.58172 4 4 7.58172 4 12C4 16.4183 7.58172 20 12 20ZM7 13H9C9 14.6569 10.3431 16 12 16C13.6569 16 15 14.6569 15 13H17C17 15.7614 14.7614 18 12 18C9.23858 18 7 15.7614 7 13ZM8 11C7.17157 11 6.5 10.3284 6.5 9.5C6.5 8.67157 7.17157 8 8 8C8.82843 8 9.5 8.67157 9.5 9.5C9.5 10.3284 8.82843 11 8 11ZM16 11C15.1716 11 14.5 10.3284 14.5 9.5C14.5 8.67157 15.1716 8 16 8C16.8284 8 17.5 8.67157 17.5 9.5C17.5 10.3284 16.8284 11 16 11Z"></path></svg>



    <div class="flex">
        <b><p>{product}</p></b>


        <div id="flex">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="40" height="40" fill="rgba(255,255,255,1)"><path fill="none" d="M0 0h24v24H0z"></path><path d="M12.0006 18.26L4.94715 22.2082L6.52248 14.2799L0.587891 8.7918L8.61493 7.84006L12.0006 0.5L15.3862 7.84006L23.4132 8.7918L17.4787 14.2799L19.054 22.2082L12.0006 18.26ZM12.0006 15.968L16.2473 18.3451L15.2988 13.5717L18.8719 10.2674L14.039 9.69434L12.0006 5.27502L9.96214 9.69434L5.12921 10.2674L8.70231 13.5717L7.75383 18.3451L12.0006 15.968Z"></path></svg>
            <b><p>{rating}</p></b>
        </div>
    </div>   



        <CategoryButton
        link={"/"}
        category={"Add To Wishlist"}
        svg={"M15.3709 3.44L18.5819 9.002L22.0049 9.00218V11.0022L20.8379 11.002L20.0813 20.0852C20.0381 20.6035 19.6048 21.0022 19.0847 21.0022H4.92502C4.40493 21.0022 3.97166 20.6035 3.92847 20.0852L3.17088 11.002L2.00488 11.0022V9.00218L5.42688 9.002L8.63886 3.44L10.3709 4.44L7.73688 9.002H16.2719L13.6389 4.44L15.3709 3.44ZM18.8309 11.002L5.17788 11.0022L5.84488 19.0022H18.1639L18.8309 11.002ZM13.0049 13.0022V17.0022H11.0049V13.0022H13.0049ZM9.00488 13.0022V17.0022H7.00488V13.0022H9.00488ZM17.0049 13.0022V17.0022H15.0049V13.0022H17.0049"}/>

        <CategoryButton
        link={"/"}
        category={"Compare"}
        svg={"M12.9985 2L12.9979 3.278L17.9985 4.94591L21.631 3.73509L22.2634 5.63246L19.2319 6.643L22.3272 15.1549C21.2353 16.2921 19.6996 17 17.9985 17C16.2975 17 14.7618 16.2921 13.6699 15.1549L16.7639 6.643L12.9979 5.387V19H16.9985V21H6.99854V19H10.9979V5.387L7.23192 6.643L10.3272 15.1549C9.23528 16.2921 7.69957 17 5.99854 17C4.2975 17 2.76179 16.2921 1.66992 15.1549L4.76392 6.643L1.73363 5.63246L2.36608 3.73509L5.99854 4.94591L10.9979 3.278L10.9985 2H12.9985ZM17.9985 9.10267L16.04 14.4892C16.628 14.8201 17.2979 15 17.9985 15C18.6992 15 19.3691 14.8201 19.957 14.4892L17.9985 9.10267ZM5.99854 9.10267L4.04004 14.4892C4.62795 14.8201 5.29792 15 5.99854 15C6.69916 15 7.36912 14.8201 7.95703 14.4892L5.99854 9.10267Z"}/> 

        <!--Hopefully we can make the link into a prop too-->


</div>



    <aside class="right">

        <div id="right">
            <h3>Filter</h3>
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" height="35px" fill="currentColor"><path fill="none" d="M0 0h24v24H0z"></path><path d="M7 3V6H3V8H7V11H9V3H7ZM11 8H21V6H11V8ZM17 13V16H21V18H17V21H15V13H17ZM13 18H3V16H13V18Z"></path></svg>
        </div>


            <StoreInformation
            store={"Store"}
            price={"100kr:-"}/>   
            <br> 
            <StoreInformation
            store={"Store"}
            price={"100kr:-"}/>   
            <br>
            <StoreInformation
            store={"Store"}
            price={"100kr:-"}/>   
            <br>
            <StoreInformation
            store={"Store"}
            price={"100kr:-"}/>   
            <br>
            <StoreInformation
            store={"Store"}
            price={"100kr:-"}/>   
            <br>
            <StoreInformation
            store={"Store"}
            price={"100kr:-"}/>   
            <br>
        <!--Hopefully we can make the store and price into props as well-->

        


    </aside>
    
</section>
<!--Above this goes for the card thingy in HTML-->

<script>
    import StoreInformation from "../pre-components/StoreInformation.svelte";
    import CategoryButton from "../pre-components/CategoryButton.svelte";
    let { product,  rating,} = $props();
</script>

