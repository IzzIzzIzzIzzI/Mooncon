<script>
    import front from "$lib/pictures/Home_Picture.png";
</script>

<link rel="stylesheet" href="https://use.typekit.net/wmh1kbd.css">
<link rel="stylesheet" href="https://use.typekit.net/wmh1kbd.css">
<link rel="stylesheet" href="https://use.typekit.net/wmh1kbd.css">

<div class="front_picture">
    <!-- svelte-ignore a11y-img-redundant-alt -->
    <img src="{front}" alt="Mooncon logo and name">
</div>

<div class="maps">
    <div class="venue_map">
        <!-- svelte-ignore a11y-missing-attribute -->
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1998.9772504702821!2d10.709955976479797!3d59.932519662593656!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x46416dc4aae9a79f%3A0xcacc32c6d9c43be6!2sChateau%20Neuf%2C%200369%20Oslo!5e0!3m2!1sen!2sno!4v1702543401785!5m2!1sen!2sno" width="400px" height="400px" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>

    <div class="map_text">
        <div class="venue_text">
            <h1>Venue location:</h1>
            <p class="place_name">Chateau Neuf</p>
            <p class="address">Slemdalsveien 15</p>
        </div>

        <div class="sleep_text">
            <h1>Sleepinghall location:</h1>
            <p class="place_name">Majorstua skole</p>
            <p class="address">Bogstadveien 74</p>
        </div>
    </div>

    <div class="sleep_map">
        <!-- svelte-ignore a11y-missing-attribute -->
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1999.1696133418352!2d10.711076676479504!3d59.929327662850774!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x46416d0b22d33d0f%3A0x7715ff0a380e6999!2sMajorstua%20school!5e0!3m2!1sen!2sno!4v1702543709145!5m2!1sen!2sno" width="400" height="400" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
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
        justify-content: center;
    }

    .venue_map {
        width: 400px;
        height: 400px;
        background-color: blueviolet;
        border-radius: 25px;
        overflow: hidden;

    }

    .map_text {
        width: 400px;
        height: 400px;
        border-radius: 25px;
        margin-left: 20px;
        margin-right: 20px;
    }

    .venue_text {
        top: 0;
        width: 400px;
        height: 200px;
        color: white;
    } .venue_text h1 {
        margin: 0;
        font-family: Latienne-Pro;
        font-style: medium;
        text-decoration: underline;
    } 

    .sleep_text {
        bottom: 0;
        width: 400px;
        height: 200px;
        color: white;
        text-align: right;
    } .sleep_text h1 {
        margin: 0;
        font-family: Latienne-Pro;
        font-style: medium;
        text-decoration: underline;
    } 

    .place_name {
        font-family: Rockwell-Nova;
        margin: 0;
        font-size: 25px;
    }

    .address {
        font-family: Rockwell-Nova;
        margin: 0;
        font-weight: 200;
        font-size: 25px;
    }

    .sleep_map {
        width: 400px;
        height: 400px;
        background-color: blueviolet;
        border-radius: 25px;
        overflow: hidden;
    }
    
</style>