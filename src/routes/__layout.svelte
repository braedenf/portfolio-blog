<script>
    import "../app.postcss";
    import Header from '$lib/header.svelte';
    import Footer from '$lib/footer.svelte';
</script>

<Header />

<div class="mx-20 my-12">
    <slot />
</div>

<Footer />
