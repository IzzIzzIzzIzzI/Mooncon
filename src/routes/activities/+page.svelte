<script>
    import friday from "$lib/pictures/Program1.png";
    import saturday from "$lib/pictures/Program2.png";
    import sunday from "$lib/pictures/Program3.png";
</script>

<link rel="stylesheet" href="https://use.typekit.net/wmh1kbd.css">
<link rel="stylesheet" href="https://use.typekit.net/wmh1kbd.css">
<link rel="stylesheet" href="https://use.typekit.net/wmh1kbd.css">

<div class="top">
    <div class="title">
        <h1>Activities</h1>
    </div>

    <div class="line_main">
    </div>
</div>

<div class="main">
    <div class="programs">
        <h2>Friday</h2>
        <img src="{friday}" alt="Spreadsheet of the program on Friday">
    </div>
    <div class="programs">
        <h2>Saturday</h2>
        <img src="{saturday}" alt="Spreadsheet of the program on Saturday">
    </div>
    <div class="programs">
        <h2>Sunday</h2>
        <img src="{sunday}" alt="Spreadsheet of the program on Sunday">
    </div>

    <div class="line_horizontal"></div>

    <div class="dnd">
        
    </div>
</div>

<style>
    .top {
        width: 100vw;
        height: 160px;
        top: 90px;
        position: absolute;
        display: flex;
        align-items: center;
        flex-direction: column;
    }

    .title {
        width: 100vw;
        height: 80px;
        justify-self: center;
        align-items: center;
        justify-content: center;
        display: flex;
    } .title h1 {
        display: flex;
        font-family: latienne-Pro;
        font-style: bold;
        color: white;
        font-size: 50px;
    }

    .line_main {
        width: 85vw;
        height: 5px;
        background-color: #3c144b;
    }

    .main {
        width: 100vw;
        top: 200px;
        display: flex;
        align-items: center;
        flex-direction: column;
        position: absolute;
    }

    .programs {
        margin-bottom: 20px;
    } .programs h2 {
        color: white;
        font-family: Latienne-Pro;
        font-style: medium;
        margin: 0px;
    }.programs img {
        border: #14001d solid;
        border-radius: 10px;
    }

    .line_horizontal {
        width: 85vw;
        height: 5px;
        margin-top: 20px;
        margin-bottom: 20px;
        background-color: #3c144b;
        opacity: 60%;
    }
</style>