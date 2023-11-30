<script>
    import { page } from "$app/stores";
    import { goto } from "$app/navigation"
</script>

<link rel="stylesheet" href="https://use.typekit.net/wmh1kbd.css">
<link rel="stylesheet" href="https://use.typekit.net/wmh1kbd.css">

<div class="back">
    <button class="mooncon" on:click={()=>{goto("/");}}>
        <h1>Mooncon</h1>
    </button>
    <div class="options">
        <button class="about_us" on:click={()=>{goto("/about_us");}}>
            <h2>About us</h2>
        </button>
        <button class="FAQ" on:click={()=>{goto("/faq");}}>
            <h2>FAQ</h2>
        </button>
        <button class="competitions" on:click={()=>{goto("/competitions");}}>
            <h2>Competitions</h2>
        </button>
        <button class="activities" on:click={()=>{goto("/activities");}}>
            <h2>Activities</h2>
        </button>
        <button class="info" on:click={()=>{goto("/info");}}>
            <h2>Info</h2>
        </button>
        <button class="tickets" on:click={()=>{goto("/tickets");}}>
            <h2>Tickets</h2>
        </button>
    </div>
</div>

<style>
    button {
        border: none;
        color: white;
        background-color: rgba(0, 0, 0, 0);
        height: fit-content;
        width: fit-content;
    }

    .back {
        width: 100%;
        height: 150px;
        background-color: #3c144b;
        position: fixed;
        border-radius: 25px;
        top: -50px;
    }

    .mooncon {
        color: white;
        right: 0;
        top: 0;
        position: fixed;
        font-family: rafaella-shadow;
        font-weight: 700;
    } .mooncon h1 {
        font-size: 50px;
        margin: 25px;
    } .mooncon h1:hover {
        cursor: pointer;
    }

    .options {
        position: fixed;
        top: 0px;
        height: 100px;
        width: 60%;
        display: flex;
        flex-direction: row;
        justify-content: left;
        justify-content: space-between;
        padding-left: 50px;
        padding-top: 15px;
    } .options h2 {
        color: white;
        font-family: Latienne Pro;
        font-size: 25px;
    } .options h2:hover {
        cursor: pointer;
    }

</style>

