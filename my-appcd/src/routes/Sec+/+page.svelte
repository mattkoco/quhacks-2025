<script>
    import Nav from "../nav.svelte"
</script>

<div id=buttText>
    <Nav></Nav>
</div>


<div id=backgroundTop>
</div>

<style>

    @import url(https://fonts.googleapis.com/earlyaccess/nicomoji.css);
    
    #backgroundTop {
        position: fixed;
        top: 20%;
        bottom: 0;
        left: 0;
        right: 0;
        background-color: #3A6D8C;
        display: flex;
        align-items: center;
        z-index: 1;
    }

    #buttText {
        font-family: 'Nico Moji';
    }

</style>