<script>
    import front from "$lib/pictures/Home_Picture.png";
</script>

<div class="front_picture">
    <!-- svelte-ignore a11y-img-redundant-alt -->
    <img src="{front}" alt="Mooncon logo and name">
</div>

<style>
    .front_picture {
        width: 100px;
        height: 100px;
        position: fixed;
        top: 300px;
        background-color: blue;
    } .front_picture img {
        width: 1250px;
        height: 1000px;
        top: 0;
        position: static;
        background-color: aqua;
    }
    
</style>