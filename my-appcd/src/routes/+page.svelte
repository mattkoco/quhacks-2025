<script>
    import Nav from "./nav.svelte";
</script>

<Nav></Nav>

<div id=background>
    <div id=text>
        Cert Helper
    </div>
</div>

<style>
    #background {
        position: fixed;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
        background-color: #2c556f;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    #text {
        font-size: 80px;
        color: aliceblue;
    }
</style>