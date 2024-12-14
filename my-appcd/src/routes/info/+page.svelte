
<script>
    import Nav from "../nav.svelte";
    import Button from "../Button.svelte";

</script>

<Nav></Nav>
<div id=backgroundTop>
    <div id="descriptions">
        <div id="about">
            About
        </div>
    </div>
</div>





<style>

    @import url(https://fonts.googleapis.com/earlyaccess/nicomoji.css);
    @import url(https://fonts.googleapis.com/css?family=Pavanam);

    #backgroundTop {
        position: fixed;
        top: 20%;
        bottom:0%;
        left: 0;
        right: 0;
        background-color: #3A6D8C;
        display: flex;
        align-items: center;
        z-index: 1;
    }

    #descriptions {

        width: 250px;
        height: 100px;
        background-color: #6A9AB0;
        border-radius: 15px;
        margin-top: -4in;
        margin-left: 42%;
    }

    #about {
        font-size: 50px;
        text-align: center;
        color: #EAD8B1;
        align-items: center;
        font-family: 'Nico Moji';
        margin-top: 6%;
    }



</style>