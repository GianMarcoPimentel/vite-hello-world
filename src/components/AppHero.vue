<script>
export default {
    name: "AppHero",
}
</script>

<template>
    <div id="jumbotron">
        <h2>
            Il mio jumbotron
        </h2>
        <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Modi fuga soluta explicabo nihil aperiam voluptas quisquam, ducimus nesciunt sit quasi amet, eum aliquam, fugit iste blanditiis esse veniam enim nam.
        </p>
        <button>
            Cliccami
        </button>
    </div>
</template>

<style>
    #jumbotron{
        display: flex;
        flex-flow: column;
        align-items: center;

        height: 600px;
        position: relative;

        padding: 20px;


    }
    #jumbotron p{
        color : red;
        text-align: center;
        padding: 20px;
        cursor: pointer;
    }

    #jumbotron p:hover{
        text-decoration: underline;
        color : purple
        
    }
    #jumbotron button{
        background-color: blue;
        color : white;

        border: none;
        border-radius: 10px;

        padding: 10px;

        cursor: pointer;
        }
</style>