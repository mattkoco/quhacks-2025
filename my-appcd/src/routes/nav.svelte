<script>
    import Button from "./Button.svelte";
</script>
<div id=nav>
    <a href="https://lbc2.org" target="_blank">
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


<style>
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