<script>

    let buttonProps = {
        class:[$$restProps.class]
    }
</script>
<button on:click
        on:mouseover
        on:mouseenter
        on:mouseleave
        {...buttonProps}>
    <slot/>
</button>

<style>

    .nav {
        position: relative;
        align-self: center;
        width: 250px;
        height: 90px;
        border-radius: 15px;
        margin-left: 10px;
    }
    .primary {
        position: relative;
        width: 500px;
        height: 200px;

        border-radius: 15px;
        margin-left: 7.5%;

        top: 10%;


    }

    .lg {
        font-size: 50px;
        background-color: #6A9AB0;
        font-family: 'Nico Moji';
        font-weight: 100;
        color: #EAD8B1;

        border-color: #EAD8B1;
        border-width: 1px;

        transition-duration: 0.4s;
    }

    .lg:hover {
        background-color: #EAD8B1;
        border-color: #6A9AB0;
        color:#6A9AB0;
    }



</style>