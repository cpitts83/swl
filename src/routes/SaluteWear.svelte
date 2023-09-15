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
		price: 26,
		quantity: 1,
		photo: "./frontogbrhoodie.png",
	},
	{
		id: "5",
		name: "Black and Silver Salute Weightlifters Hoodie",
		price: 26,
		quantity: 1,
		photo: "./backswlhoodieblk.png",
	},
	{
		id: "6",
		name: "Weakness is An Excuse Tee",
		price: 26,
		quantity: 1,
		photo: "./backwiebluogtee.png",
	},
	{
		id: "7",
		name: "Grey and White Tee",
		price: 26,
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
		price: 26,
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
		price: 56,
		quantity: 1,
		photo: "./bluteebluhatcombo.png",
	},
	{
		id: "13",
		name: "Beautiful and Strong Tee",
		price: 26,
		quantity: 1,
		photo: "./bsgrfront.png",
	},
	{
		id: "14",
		name: "Burgundy and Gold Tee",
		price: 26,
		quantity: 1,
		photo: "./burgswt-shirt.png",
	},
	{
		id: "15",
		name: "White and Black Hat Combo",
		price: 56,
		quantity: 1,
		photo: "./bwlogowhiteteehatcombo.png",
	},
	{
		id: "16",
		name: "SWL White tee and Blue Hat Combo",
		price: 56,
		quantity: 1,
		photo: "./ctrlogocombo.png",
	},
	{
		id: "17",
		name: "My physical is strong tee and Grey Hat Combo",
		price: 26,
		quantity: 1,
		photo: "./front_mphstwhgrvneck.png",
	},
	{
		id: "18",
		name: "Blue and Orange Tee",
		price: 26,
		quantity: 1,
		photo: "./Frontogblutee.png",
	},
	{
		id: "19",
		name: "Brown and Orange Salute Weightlifters Hoodie",
		price: 26,
		quantity: 1,
		photo: "./frontogbrhoodie.png",
	},
	{
		id: "20",
		name: "Grey and White Tee",
		price: 26,
		quantity: 1,
		photo: "./bkblkwhtee.png",
	},
	{
		id: "21",
		name: "Grey and White Tee",
		price: 26,
		quantity: 1,
		photo: "./bkblkwhtee.png",
	},
	{
		id: "22",
		name: "Grey and White Tee",
		price: 26,
		quantity: 1,
		photo: "./bkblkwhtee.png",
	},
	{
		id: "23",
		name: "Grey and White Tee",
		price: 26,
		quantity: 1,
		photo: "./bkblkwhtee.png",
	},
	{
		id: "24",
		name: "Grey and White Tee",
		price: 26,
		quantity: 1,
		photo: "./bkblkwhtee.png",
	},
	{
		id: "25",
		name: "Grey and White Tee",
		price: 26,
		quantity: 1,
		photo: "./bkblkwhtee.png",
	}

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