<script>
    import CardID from "../../components/CardID.svelte";
</script>

<svelte:head>
 <title>Product - TagCheck</title>  <!--Dynamic title?-->
</svelte:head>

<CardID
product={"Whatever product"}
rating={"10"}/>

<!---->


<!--

The needed tools for the unsuccessful dynamic routing

<script>
const { product } =  data;
let { data, children } = $props();
</script>


{@render children()}
<h1>{product.title}</h1>
<p>{product.description}</p>
<p>{product.price.toFixed(2)}</p>

-----------------------------------------------------------------------------------------------
For a '+page.js' file:

export const load = ({fetch, params}) => {
const fetchProduct = async (id) => {
    const res = await fetch //and an API
    const data = res.json()
    return data
}

return {
    product: fetchProduct(params.productID)
}

}

-->



<!--  https://www.youtube.com/watch?v=gNgQFF-tmuo   -->