<script>
    import Navbar from "$lib/components/navbar.svelte";

</script>

<div class="background"></div>

<slot/>
<Navbar/>

<style>
    .background {
        height: 100%;
        width: 100%;
        background-image: linear-gradient(#945aaa 60%, #5a5aaa);
        position: fixed;
    }

</style>