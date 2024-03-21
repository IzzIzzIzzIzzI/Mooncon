<script>
    import friday from "$lib/pictures/Program1.png";
    import saturday from "$lib/pictures/Program2.png";
    import sunday from "$lib/pictures/Program3.png";
    import floor0 from "$lib/pictures/Basement.png";
    import floor1 from "$lib/pictures/Floor1.png";
    import floor2 from "$lib/pictures/Floor2.png";
    import floor3 from "$lib/pictures/Floor3.png";
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
        <div class="dnd_text">
            <h2>D&D</h2>
            <p>Lorem ipsum dolor sit amet. Id nisi illo aut voluptatum similique qui rerum officiis! Ea recusandae placeat ut repellat cupiditate At molestiae earum ad nesciunt autem est provident sint. Est culpa earum et fugit ullam non omnis ipsum et corrupti earum At sunt voluptatum. Et laudantium culpa ad commodi voluptas sit voluptas totam est amet nisi ex enim labore qui assumenda ipsum non velit sapiente.</p>
        </div>
        <div class="line_vertical"></div>
        <div class="dnd_times">

        </div>
    </div>

    <div class="line_horizontal"></div>

    <div class="maps">
        <img src="{floor0}" alt="Map of the basement">
        <img src="{floor1}" alt="Map of the first floor">
        <img src="{floor2}" alt="Map of the second floor">
        <img src="{floor3}" alt="Map of the third floor">
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
        font-size: xx-large;
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

    .dnd{
        display: flex;
        flex-direction: row;
    }

    .dnd_text {
        display: flex;
        flex-direction: column;
        width: 35vw;
    } .dnd_text h2 {
        color: white;
        font-family: Latienne-Pro;
        font-style: medium;
        font-size:xx-large;
        margin-bottom: 0;
        
    } .dnd_text p {
        color: white;
        font-family: Rockwell-Nova;
        font-style: regular;
        font-size: large;
        margin-top: 0;
    }

    .line_vertical {
        width: 5px;
        background-color: #3c144b;
        opacity: 60%;
        margin-left: 20px;
        margin-right: 20px;
        
    }

    .dnd_times {
        width: 30vw;
        height: 30vw;
        background-color: black;
        margin-left: 40px;
    }

    .maps {
        display: grid;
        grid-template-columns: auto auto;
        margin-bottom: 50px;
    } .maps img {
        width: 35vw;
        margin: 15px;
    }
</style>