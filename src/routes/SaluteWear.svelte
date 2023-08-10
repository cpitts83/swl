<script lang="ts">
import ProductCard from "$lib/productCard.svelte";


const products : Product[] = [
	{
		id: "1",
		name: "Salute Weightlifters Tee",
		price: 26,
		quantity: 1,
		photo: './authswlwhitetee.png',
	},
	{
		id: "2",
		name: "Beautiful and Strong Purple Hoodie",
		price: 56,
		quantity: 1,
		photo: "./backbspurplehoodie.png",
	},
	{
		id: "3",
		name: "Burgundy Salute Weightlifters Tee",
		price: 26,
		quantity: 1,
		photo: "./backburgswt-shirt.png",
	},
	{
		id: "4",
		name: "Brown and Orange Salute Weightlifters Hoodie",
		price: 25,
		quantity: 1,
		photo: "./frontogbrhoodie.png",
	},
	{
		id: "5",
		name: "Black and Silver Salute Weightlifters Hoodie",
		price: 25,
		quantity: 1,
		photo: "./backswlhoodieblk.png",
	},
	{
		id: "6",
		name: "Weakness is An Excuse Tee",
		price: 25,
		quantity: 1,
		photo: "./backwiebluogtee.png",
	},
	{
		id: "7",
		name: "Grey and White Tee",
		price: 25,
		quantity: 1,
		photo: "./bkblkwhtee.png",
	},
	{
		id: "8",
		name: "Black and White Hoodie & Hat Combo",
		price: 80,
		quantity: 1,
		photo: "./blkhathoodiecombo.png",
	},
	{
		id: "9",
		name: "Dark Grey and Silver Tee",
		price: 26,
		quantity: 1,
		photo: "./blkswlteefr.png",
	},
	{
		id: "10",
		name: "Blue Salute Weightlifters Hat",
		price: 25,
		quantity: 1,
		photo: "./bluehat.png",
	},
	{
		id: "11",
		name: "Sky Blue Tee and Blue Hat Combo",
		price: 56,
		quantity: 1,
		photo: "./bluhtteecombo.png",
	},
	{
		id: "12",
		name: "Blue and White Hat and Tee Combo",
		price: 25,
		quantity: 1,
		photo: "./bluteebluhatcombo.png",
	},
	{
		id: "13",
		name: "Grey and White Tee",
		price: 25,
		quantity: 1,
		photo: "./bkblkwhtee.png",
	},
	{
		id: "14",
		name: "Grey and White Tee",
		price: 25,
		quantity: 1,
		photo: "./bkblkwhtee.png",
	},
]
</script>



<div class="container h-full mx-auto flex justify-center items-center">
	<section class="grid grid-cols-5 gap-3">
		<article class="col-span-5">
			<h1 class="text-4xl">Salute Weightlifters</h1>
		</article>
		{#each products as product}
        <ProductCard product={product}/>
		{/each}
		<span class="col-span-5">
			<button class="btn variant-filled-warning">Checkout</button>
		</span>
	</section>
</div>