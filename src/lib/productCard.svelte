
<script lang="ts">
    export let product : Product = {id: "", name: "", price: 0, quantity: 0, photo: ""};
    console.log(product)
</script>


<article class="container card p-4 variant-glass-surface">
    <img src={product.photo} alt="" srcset="">
    <header class="card-header">
        <h2>{product.name}</h2>
    </header>


    <article class="card-body px-4">
        Quantity: <strong>5</strong>
    </article>
    <article class="card-body px-4">
       <h3>Price {product.price}</h3> 
    </article>
    <footer class="card-footer">
        <button class="p-2 rounded-md variant-glass-success">Add</button>
        <button class="p-2 rounded-md variant-glass-error">Remove</button>
        
    </footer>
</article>