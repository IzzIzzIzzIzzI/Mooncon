<script>
    import front from "$lib/pictures/Home_Picture.png";
</script>

<div class="front_picture">
    <!-- svelte-ignore a11y-img-redundant-alt -->
    <img src="{front}" alt="Mooncon logo and name">
</div>

<div class="maps">
    <div class="venue_map">

    </div>

    <div class="map_text">
        <div class="venue_text">

        </div>

        <div class="sleep_text">

        </div>
    </div>

    <div class="sleep_map">

    </div>
</div>

<style>
    .front_picture {
        width: 100px;
        height: 100px;
        position: absolute;
        top: 50px;
    } .front_picture img {
        width: 1366px;
        height: 650px;
        top: 0;
        position: static;
    }

    .maps {
        width: 100%;
        height: fit-content;
        position: absolute;
        top: 700px;
        display: flex;
        flex-direction: row;
        justify-content: space-around;
    }

    .venue_map {
        width: 400px;
        height: 400px;
        background-color: aqua;
        border-radius: 25px;
    }

    .map_text {
        width: 400px;
        height: 400px;
        background-color: blue;
        border-radius: 25px;
    }

    .sleep_map {
        width: 400px;
        height: 400px;
        background-color: aqua;
        border-radius: 25px;
    }
    
</style>