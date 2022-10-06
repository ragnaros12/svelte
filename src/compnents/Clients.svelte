<section class="container clients">
    <a name="sotr" class="title-clients">Наши сотрудники</a>
    <div class="container-clients">
        <div class="item-client">
            <img src="images/tolya.png" class="image-item-client">
            <div class="text-container-item-client">
                <div class="title-item-client">Толя</div>
                <div class="subtitle-item-client">Барбер</div>
            </div>
        </div>
        <div class="item-client">
            <img src="images/oleg.png" class="image-item-client">
            <div class="text-container-item-client">
                <div class="title-item-client">Олег</div>
                <div class="subtitle-item-client">Старший барбер</div>
            </div>
        </div>
        <div class="item-client">
            <img src="images/shax.png" class="image-item-client">
            <div class="text-container-item-client">
                <div class="title-item-client">Шах</div>
                <div class="subtitle-item-client">Топ-Барбер</div>
            </div>
        </div>
        <div class="item-client">
            <img src="images/shaxram.png" class="image-item-client">
            <div class="text-container-item-client">
                <div class="title-item-client">Шахрам</div>
                <div class="subtitle-item-client">Топ-Барбер</div>
            </div>
        </div>
    </div>
</section>

<style>
    .clients{
        flex-direction: column;
        margin-bottom: 30px;
    }
    .title-clients{
        font-size: 40px;
        margin: 50px auto 20px;
    }
    .container-clients{
        width: 90%;
        margin: auto;
        flex-wrap: wrap;
        display: flex;
        justify-content: space-around;
    }
    .item-client{
        height: 440px;
        width: 270px;
        margin-top: 20px;
        display: flex;
        flex-direction: column;
        background: rgb(83, 71, 62);
    }
    .image-item-client{
        width: 270px;
    }
    .text-container-item-client{
        width: 100%;
        height: 100%;
    }
    .title-item-client{
        font-size: 30px;
        color: white;
        margin-top: 10px;
        text-align: center;
    }
    .subtitle-item-client{
        font-size: 25px;
        margin-top: 10px;
        text-align: center;
        color: #d3a278;
    }
    .item-client:hover{
        transform: scale(1.1);
        box-shadow: 5px 5px 10px rgb(0 0 0 / 50%);
        cursor: pointer;
        transition: all 1s;
    }
</style>