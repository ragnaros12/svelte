<div class="navigation" id="navigation">
    <div class="list-nav">
        <a href="#usl" class="item-nav">Услуги</a>
        <a href="#diff" class="item-nav">В чем разница?</a>
        <a href="#sotr" class="item-nav">Сотрудники</a>
        <a href="#acc" class="item-nav">Акции</a>
        <a href="#why" class="item-nav">Почему мы?</a>
        <a href="#contacts" class="item-nav">Контакты</a>
    </div>
    <img alt="" src="images/close.png" class="navigation-close" id="navigation-close">
</div>
<style>
    @media (max-width: 550px) {
        .item-nav{
            font-size: 25px;
        }
        .list-nav{
            height: 70%;
            margin: auto;
        }
        .navigation-close{
            height: 20px;
            width: 20px;
            margin-left: -40px;
            margin-top: 20px;
        }
    }
    .item-nav{
        text-align: center;
        font-size: 35px;
        color: white;
    }
    .list-nav{
        width: 400px;
        height: 80%;
        margin: auto;
        display: flex;
        flex-direction: column;
        justify-content: space-around;
    }

    .navigation{
        z-index: 999;
        position: fixed;
        background: #2c241d;
        width: 100%;
        height: 100%;
        top: -100%;
        display: flex;
    }
    .navigation-close{
        width: 40px;
        height: 40px;
        left: 100%;
        margin-left: -80px;
        position: absolute;
        margin-top: 30px;
    }
    .navigation-close:hover{
        cursor: pointer;
    }

</style>