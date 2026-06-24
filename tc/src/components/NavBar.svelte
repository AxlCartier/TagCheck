<style>

nav {
    display: flex;

    padding: 20px 25px;
    justify-content: space-between;
    align-items: center;
    gap: 100px;



    border-bottom: 1px solid black;
    position: sticky;

    background-color: rgb(179, 179, 179);

}

nav .non-menu {
    display: flex;
    flex-direction: row;

    justify-content: space-between;
    align-content: space-between;


    padding: 20px 25px;
}

nav img {
    width: 80px;
    height: 100%;
}

nav a {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-self: center;
    color: black;/*var(--c);*/
}

a:hover {
    color: #4a7aff; /*var(--primary)*/
    transition: 0.5s ease-out;
}

nav .menu {
    display: none;
}

@media (max-width:0px) {

    nav .non-menu a {
    display: none;
    z-index: -10000;
  }

    .menu {
    display: flex;
    flex-direction: column;

    justify-content: flex-end;
    align-self: flex-end;
    background-color: rgb(179, 179, 179);
    color: black;/*var(--c);*/
    z-index: 2890;

    height: 100%;
    width: fit-content + 10px;
    gap: 10px;
    border: 1px solid black;
  }
}



</style>


<!--Below this goes for the navigation bar-->



    


<nav>
    <div class="non-menu">
        <img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/e716439e-13ee-4fb9-857f-387a9bdb6c5c/dm3lxre-bf6a2d2e-c14f-48a8-ae44-390ea454bd3f.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiIvZi9lNzE2NDM5ZS0xM2VlLTRmYjktODU3Zi0zODdhOWJkYjZjNWMvZG0zbHhyZS1iZjZhMmQyZS1jMTRmLTQ4YTgtYWU0NC0zOTBlYTQ1NGJkM2YucG5nIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.bhkhjOmBUaokb4WhFpozBOQd1Z1THzqUCyonA2S-Hxo" alt="">


       <a href="#categories"><b><p>Categories</p></b></a> <!--???-->
       <a href="#compare"><b><p>Compare</p></b></a>
       <a href="/"><b><p>About</p></b></a> <!--????????-->
    </div>
</nav>


<div class="menu"></div>








<!--Above this goes for the navigation bar-->



