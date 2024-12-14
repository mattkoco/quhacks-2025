<body>
    <nav id=nav>
        <div id=navText>
            <a href="use later" class="navText">add smth</a>
            <a href="use later" class="navText">add smth</a>
            <a href="use later" class="navText">add smth</a>
        </div>
    </nav>
</body>

<style>
    * {
        box-sizing: border-box;
        z-index: 50;
    }

    body {
        margin: 0;
        padding: 0;
    }

    #nav {
        position: sticky;
        padding: 0 2.8em;
        padding-bottom: 1em;
        padding-top: 1em;
        background-color: black;
        font-size: 1.5em;
        border-bottom: solid 0.13em white;
        display: flex;
        align-items: center;
    }

    #navText {
        display: flex;
        gap: 1.5em;
        font-weight: 600;
        flex-grow: 1;
    }

    #navText > *{
        color: white;
        text-decoration: none;
    }


</style>