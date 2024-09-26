<div id="main">
    <div class="heading">
        <h1>Hello!</h1> I am <span>Aaska Koirala.</span>
    </div>
</div>


<style>
    #main {
        width: 100vw;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        background: #003034;
    }
    .heading{
        font-size: 6rem;
        font-weight: 800;
        color: rgb(255, 255, 255);
        padding-inline: 0.5rem;
        text-align: center;
    }
    span{
        color: #FFD700;
    }
    :global(body){
        margin: 0;
        padding: 0;
    }
    h1{
        animation: bounce 1s infinite;
    }
    h1::before{
        content: '<h1>';
        font-family: 'La Belle Aurore', cursive;
        color: #ffd700;
        font-size: 1rem;
    }
    h1::after{
        content: '</h1>';
        font-family: 'La Belle Aurore', cursive;
        color: #ffd700;
        font-size: 1rem;
    }
</style>