<script>
    import Nav from "./nav.svelte";
</script>

<Nav></Nav>

<div id=backgroundTop>
    <div id=title>
        Cert-<br>Breeze
    </div>
</div>
<div id="backgroundMid">
    <div id="desc">
        Cert-Breeze is an application designed to make the certification studying<br> process a breeze, by providing endless practice questions for the certification<br> of your choice, in an easy-to-use, multiple choice format.
    </div>
</div>

<style>

    @import url(https://fonts.googleapis.com/earlyaccess/nicomoji.css);
    @import url(https://fonts.googleapis.com/css?family=Pavanam);

    #backgroundTop {
        position: fixed;
        top: 20%;
        bottom:40%;
        left: 0;
        right: 0;
        background-color: #3A6D8C;
        display: flex;
        align-items: center;
        z-index: 1;
    }
  

    #backgroundMid {
        position: fixed;
        top: 60%;
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