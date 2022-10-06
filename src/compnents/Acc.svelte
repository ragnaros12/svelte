<section class="container acc">
    <a name="acc"></a>
    <div class="container-acc">
        <div class="container-text-acc">
            <div class="bg-acc dark-bg">
                <h3>Скидка 15% именинникам</h3>
                <h4>В День рождения на все наши услуги действует скидка 15%, а также 3 дня до и после праздника	</h4>
            </div>
            <div class="bg-acc light-bg">
                <h3>Счастливые часы</h3>
                <h4>Скидка 15% рассчитывается на общий чек при посещении нашего барбершопа <strong>с Понедельника по Четверг с 10:00 до 15:00</strong></h4>
            </div>
        </div>
        <div class="container-text-acc1">
            <img src="images/kreslo.png" style="position: absolute; width: 450px; margin-left: -130px; margin-top: -60px">
            <h3>Первое посещение</h3>
            <h4>Скидка 20% на первое посещение</h4>
            <h4>Скидка расчитывается на общий чек</h4>
        </div>
        <div class="container-text-acc2">
            <div>*Акции не суммируются</div>
        </div>
    </div>
</section>

<style>
    .container-acc{
        display: flex;
        flex-direction: column;
        width: 85%;
        height: 85vh;
        margin: 20px auto;
    }
    .container-text-acc{
        height: 50%;
        width: 100%;
        display: flex;
    }
    .container-text-acc1{
        height: 40%;
        width: 100%;
        display: flex;
        flex-direction: column;
        border-bottom: 2px solid white;
        background: #5f544c;
    }
    .container-text-acc2{
        height: 10%;
        width: 100%;
        display: flex;
        background: #33302e;
    }
    .container-text-acc1 *{
        color: white;
        margin-left: auto;
        margin-right: auto;
    }
    .container-text-acc1 h3{
        font-weight: bold;
        margin-top: 40px;
        font-size: 40px;
    }

    .container-text-acc1 h4{
        margin-top: 20px;
        font-weight: initial;
        font-size: 30px;
    }
    .container-text-acc1 h4:last-child{
        margin-top: 5px;
    }

    .container-text-acc2 div{
        font-size: 30px;
        margin: auto;
        color: white;
    }
    .bg-acc{
        width: 50%;
        padding-top: 30px;
        flex-direction: column;
        height: 100%;
    }
    .bg-acc h3{
        font-size: 35px;
        margin-left: 20px;
        margin-top: 15px;
    }
    .bg-acc h4{
        font-weight: initial;
        margin-top: 10px;
        margin-left: 20px;
        padding-right: 10px;
        font-size: 27px;
    }
    .dark-bg{
        background: #927861;
        border-right: 1px solid white;
    }
    .light-bg{
        background: #a38871;
        border-left: 1px solid white;
    }
    .container-text-acc *{
        color: white;
    }
    @media (max-width: 1200px) {
        .bg-acc h4{
            font-size: 23px;
        }
        .bg-acc h3{
            font-size: 30px;
        }
        .container-text-acc1 h3{
            font-size: 30px;
        }
        .container-text-acc1 h4{
            font-size: 23px;
            margin-top: 40px;
        }
    }
    @media (max-width: 1000px) {
        .container-text-acc{
            flex-direction: column;
        }
        .bg-acc h4, .bg-acc h3{
            margin-left: 30px;
        }
        .bg-acc h4{
            font-size: 18px;
        }
        .bg-acc h3{
            font-size: 25px;
        }
        .bg-acc{
            padding-top: 10px;
            width: 100%;
            height: 50%;
            border: none;
            border-bottom: 2px solid white;
        }
        .container-acc{
            height: 95vh;
        }
    }
</style>