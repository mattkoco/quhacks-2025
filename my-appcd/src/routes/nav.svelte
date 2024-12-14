<script>
    import Button from "./Button.svelte";
</script>
<div id="buttText">
    <div id=nav>
        <a href="./Sec+" target="_blank">
            <Button class="nav lg">
                Sec+
            </Button>
        </a>
        <a href="https://lbc2.org" target="_blank">
            <Button class="nav lg">
                Net+
            </Button>
        </a>
        <a href="https://lbc2.org" target="_blank">
            <Button class="nav lg">
                A+
            </Button>
        </a>
        <a href="./" target="_blank">
            <Button class="nav lg">
                Home
            </Button>
        </a>
    </div>
</div>


<style>

    @import url(https://fonts.googleapis.com/earlyaccess/nicomoji.css);
    @import url(https://fonts.googleapis.com/css?family=Pavanam);

    #buttText {
        font-family: "Nico Moji";
    }

    #nav {
        position: fixed;
        top: 0;
        bottom: 75%;
        left: 0;
        right: 0;
        background-color: #001F3F;
        display: flex;
        justify-content: center;
        align-items: center;
        z-index: 6;
    }
</style>