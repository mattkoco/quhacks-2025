<script>
    import Nav from "../nav.svelte"
</script>

<div id=buttText>
    <Nav></Nav>
</div>


<div id=backgroundTop>
    <div id=QuestionBox>
        <div id="QuestionText">
            CompTIA Security+ 701 Questions
        </div>
        <div id="QuestionNum">
            Question 1:
            <div id="Question">
                Who glazes Matthew Koco every day:
            </div>
            <div id="QuesiotnOpps">
                <p id="opp1">
                    Tubby
                </p>
                <p id="opp2">
                    Max Mayfield
                </p>
                <p id="opp3">
                    CT
                </p>
                <p id="opp4">
                    Joshua
                </p>
            </div>
        </div>
    </div>
    <div id=ScoreBox>
    </div>
</div>

<style>

    @import url(https://fonts.googleapis.com/earlyaccess/nicomoji.css);
    @import url(https://fonts.googleapis.com/css?family=Pavanam);

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

    #QuestionBox {
        background-color: #6A9AB0;
        width: 800px;
        height: 80%;
        margin-left: 10%;
        border-radius: 2%;
    }

    #ScoreBox {
        background-color: #6A9AB0;
        width: 600px;
        height: 80%;
        margin-right: 10%;
        border-radius: 2%;
        margin-left: 30%;
    }

    #QuestionText {
        justify-content: center;
        align-items: center;
        text-align: center;
        margin-top: 25px;
        font-size: 40px;
        color: #EAD8B1;
    }

    #buttText {
        font-family: 'Nico Moji';
    }

    #QuestionNum {
        padding-left: 15%;
        margin-bottom: 25px;
        margin-top: 25px;
        font-size: 30px;
        color: #EAD8B1;
        width: 100%;
        margin-bottom: 20px;
        padding-bottom: 2px;
        font-family: 'Pavanam'

    }

    #QuesiotnOpps {
        padding-left: 5%;
        margin-left: 50px;
        font-family: 'Pavanam'
    }

    #Question {
        padding-left: 5%;
        width: 50vp;
        font-family: 'Pavanam'
    }
</style>