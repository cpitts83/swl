<script>
    import Logo from '$lib/prodpics/logo.png'
</script>
<nav class="card p-4 variant-glass-primary">
    <ul class="header flex justify-between items-center">
        <a href="/"><img src={Logo} alt="" srcset=""></a>
        <div class="flex space-x-4">
            <li><a href="/about" class="text-filled-primary hover:text-warning-600">About</a></li>
            <li><a href="/blog" class="text-filled-primary hover:text-warning-600">Blog</a></li>
            <li><a href="/salutewearpage" class="text-filled-primary hover:text-warning-600">Salute Wear</a></li>
        </div>
    </ul>
</nav>

<style>
    .header {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    img {
        width: 10rem;
        height: 10rem;
    }
</style>
