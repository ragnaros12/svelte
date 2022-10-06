<section class="container why">
    <a name="why"></a>
    <div class="container-why">
        <div class="container-text">
            <div class="container-why-text">
                <h3>1</h3>
                <div class="container-why-texts">
                    <h3>Стерильность</h3>
                    <h4>Полная стерилизация<br> всего оборудования</h4>
                </div>
            </div>
            <div class="container-why-text">
                <h3>2</h3>
                <div class="container-why-texts">
                    <h3>Профессиональная косметика</h3>
                    <h4>Используем только лучшую<br> косметику, известных <br> мировых брендов</h4>
                </div>
            </div>
        </div>
        <img src="images/image-why.png" style="height: 300px;margin: auto">
        <div class="container-text">
            <div class="container-why-text">
                <h3>3</h3>
                <div class="container-why-texts">
                    <h3>Качество</h3>
                    <h4>У нас работают только <br> профессионалы <br> высокого класса</h4>
                </div>
            </div>
            <div class="container-why-text">
                <h3>4</h3>
                <div class="container-why-texts">
                    <h3>Приятная атмосфера</h3>
                    <h4>Очень позитивные и <br> доброжелательные <br> барберы</h4>
                </div>
            </div>
        </div>
    </div>

</section>

<style>
    .container-why{
        width: 80%;
        display: flex;
        margin: 50px auto 20px;
        justify-content: space-between;
    }
    .container-text{
        height: 100%;
        flex-direction: column;
        justify-content: space-between;
        display: flex;
        width: 45%;
    }
    .container-image{
        display: flex;
        height: 100%;
    }

    .container-why-text{
        display: flex;
        margin-left: auto;
        margin-right: auto;
        width: 400px;
    }
    .container-why-text h3{
        font-size: 150px;
        color: #8f705650;
    }
    .container-why-texts h3{
        font-size: 30px;
        color: #ae825d;
    }
    .container-why-texts h4{
        font-size: 22px;
        margin-top: 10px;
        font-weight: lighter;
    }
    .container-why-texts{
        display: flex;
        margin-left: 20px;
        margin-top: 40px;
        flex-direction: column;
    }

    @media (max-width: 1152px) {
        .container-why img{
            display: none;
        }
        .container-why-text{
            width: 450px;
        }
    }
    @media (max-width: 945px) {
        .container-text{
            margin-left: auto;
            margin-right: auto;
            width: initial;
        }
        .container-why{
            flex-direction: column;
        }
    }
    @media (max-width: 500px) {
        .container-why-text h3 {
            font-size: 100px;
        }

        .container-why-texts h3 {
            font-size: 25px;
        }

        .container-why-texts h4 {
            font-size: 17px;
        }

        .container-why-texts {
            margin-top: 20px;
        }
    }
</style>