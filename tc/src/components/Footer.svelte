<style>
    footer {
    display: flex;
    flex-direction: column;
    flex-wrap: wrap; 
    justify-content: center;
    align-items: center;
    gap: 15px;

    padding: 10px 20px;

    background-color: rgb(179, 179, 179);
}

.main-foot {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 20px;

    gap: 100px;

    gap: 20px;
}


.main-foot img {
    width: 200px;
}

.main-foot ul {
    flex: 1;
    height: 200px;
}

@media (max-width: 800px) {
    .main-foot img {
        width: 150px;
    }

    footer, .main-foot {
        flex-direction: column;
        justify-content: flex-start;
        align-items: center;
        text-align: center;
    }
}
</style>


<!--Below this goes for the hero section in HTML-->

<footer>
    <div class="main-foot">   
        <img width="" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/e716439e-13ee-4fb9-857f-387a9bdb6c5c/dm3lxre-bf6a2d2e-c14f-48a8-ae44-390ea454bd3f.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiIvZi9lNzE2NDM5ZS0xM2VlLTRmYjktODU3Zi0zODdhOWJkYjZjNWMvZG0zbHhyZS1iZjZhMmQyZS1jMTRmLTQ4YTgtYWU0NC0zOTBlYTQ1NGJkM2YucG5nIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.bhkhjOmBUaokb4WhFpozBOQd1Z1THzqUCyonA2S-Hxo" alt="">

        

    <ul>
        <h3><b>Categories</b></h3>
        <a href="#categories"><li><p>Search Products</p></li></a>
        <a href="#filter"><li><p>Find the cheapest products</p></li></a>
        <a href="#compare"><li><p>Compare products</p></li></a>
    </ul>

    <ul>
        <h3><b>Products</b></h3>
        <a href="#gaming"><li><p>Gaming</p></li></a>
        <a href="#electronics"><li><p>Electronics</p></li></a>
        <a href="#consoles"><li><p>Consoles</p></li></a>
        <a href="#computers"><li><p>Computers</p></li></a>
        <a href="#hardware"><li><p>Hardware</p></li></a>
    </ul>

    <ul>
        <h3><b>About Us</b></h3>
        <a href="/"> <li> <p> Why us? </p> </li> </a>
        <a href="/"> <li> <p> Contact  </p> </li> </a>
     </ul>
    </div>
    

        <p id="copyright">© 2026 TagCheck</p>

</footer>


<!--Above this goes for the hero section in HTML-->