<script>
    import logo from "$lib/pictures/Mooncon_logo.png";
    import cloud1 from "$lib/pictures/Cloud1.png";
    import cloud2 from "$lib/pictures/Cloud2.webp";
    import cloud3 from "$lib/pictures/Cloud3.png";
</script>

<link rel="stylesheet" href="https://use.typekit.net/wmh1kbd.css">
<link rel="stylesheet" href="https://use.typekit.net/wmh1kbd.css">
<link rel="stylesheet" href="https://use.typekit.net/wmh1kbd.css">

<div class="top">
    <div class="title">
        <h1>Tickets</h1>
    </div>
    <div class="line">

    </div>
</div>

<div class="logo">
    <img src="{logo}" alt="Clouds infront of Mooncon logo">
</div>

<div class="clouds">
    <div class="cloud_one">
        <img src="{cloud1}" alt="Clouds infront of Mooncon logo">
    </div>

    <!-- <div class="cloud_two">
        <img src="{cloud2}" alt="Clouds infront of Mooncon logo">
    </div>

    <div class="cloud_three">
        <img src="{cloud3}" alt="Clouds infront of Mooncon logo">
    </div> -->
</div>

<style>
    .top {
        width: 100vw;
        height: 110px;
        top: 100px;
        position: absolute;
        /* background-color: blue; */
        display: flex;
        align-items: center;
        flex-direction: column;
    }

    .title {
        width: 100vw;
        height: 100px;
        /* background-color: blueviolet; */
        justify-self: center;
        align-items: center;
        justify-content: center;
        display: flex;
    } .title h1 {
        display: flex;
        font-family: latienne-Pro-Bold;
        color: white;
        font-size: 50px;
    }

    .line {
        width: 85vw;
        height: 5px;
        background-color: #3c144b;
    }

    .logo {
        width: 100vw;
        height: 65vh;
        top: 210px;
        position: absolute;
        display: flex;
        align-items: center;
        justify-content: center;
    } .logo img{
        width: 40vw;
    }

    .clouds {
        display: flex;
        width: 100vw;
        height: 65vh;
        background-color: blue;
        position: absolute;
        top: 210px;
        opacity: 50%;
    }

    .cloud_one {
        width: 30vw;
        height: 20vw;
        left: 300px;
        position: relative;
        background-color: aqua;
    } .cloud_one img {
        width: 30vw;
    }
</style>