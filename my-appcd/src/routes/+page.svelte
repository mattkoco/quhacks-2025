<script>
    import Nav from "./nav.svelte";
    import Button from "./Button.svelte"
</script>

<Nav></Nav>

<div id=backgroundTop>
    <div id=title>
        Cert-<br>Breeze
    </div>
    <div id="infoBox">
        <div id="infoText">
            Click below for more information about who we are.
        </div>
        <a href="https://lbc2.org" target=”_blank”>
            <Button class="primary lg">
                Info
            </Button>
        </a>

    </div>

</div>
<div id="backgroundMid">
    <div id="desc">
        Cert-Breeze is an application designed to make the certification studying<br> process a breeze, by providing practice questions for the certification<br> of your choice, in an easy-to-use, multiple choice format.
    </div>
</div>



<style>

    @import url(https://fonts.googleapis.com/earlyaccess/nicomoji.css);
    @import url(https://fonts.googleapis.com/css?family=Pavanam);

    #backgroundTop {
        position: fixed;
        top: 20%;
        bottom:30%;
        left: 0;
        right: 0;
        background-color: #3A6D8C;
        display: flex;
        align-items: center;
        z-index: 1;
    }

    #infoBox {
        padding-top: 15px;
        padding-bottom: 15px;
        border-radius: 15px;
        position: relative;
        left: 21%;
        top: 4.5%;
        background-color: #001F3F;
        width: 600px;
        height: 280px;

    }
    #infoText {

        font-size: 25px;
        color: #EAD8B1;
        text-align: center;
        font-family: 'Pavanam';
        font-weight: 100;
    }


    #backgroundMid {
        position: fixed;
        top: 70%;
        bottom: 0;
        left: 0;
        right: 0;
        background-color: #6A9AB0;
        display: flex;
        justify-content: center;
        align-items: center;
        z-index: 2;
    }


    #title {
        font-size: 110px;
        color: #EAD8B1;
        left: 0;
        padding-left: 0.5em;
        font-family: 'Nico Moji';
    }

    #desc {
        font-size: 40px;
        color: #EAD8B1;
        text-align: center;
        font-family: 'Pavanam';
        font-weight: 100;
    }
</style>