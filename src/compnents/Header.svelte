<header class="header">
    <div class="header-container">
        <div class="container-menu">
            <img id="burger" src="images/burger.png" alt="">
        </div>
        <img class="image" src="images/image.png" alt="">

        <div class="container-info-header">
            <a href="tel:+79110336371" class="phone">+7 (911) 033-63-71</a>
            <div class="days">
                Ежедневно с 10:00-23:00
            </div>
        </div>
    </div>
</header>

<style>

    .header-container {
        background: #1e1e1e99;
        position: absolute;
        width: 100%;
        height: 130px;
        display: flex;
        justify-content: space-between;
    }

    .image {
        height: 100px;
        margin: auto;

    }

    #burger {
        height: 40px;
        margin: auto auto auto 7%;
    }

    .container-menu{
        display: flex;
        margin-top: auto;
        margin-bottom: auto;
        width: 400px;
    }
    header {
        height: 100px;
        position: absolute;
        width: 100%;
    }

    a {
        text-decoration: none;
    }

    .phone {
        color: #ae825d;
        font-weight: bold;
        text-align: right;
        font-size: 25px;
    }

    .container-info-header {
        display: flex;
        flex-direction: column;
        margin-top: auto;
        margin-bottom: auto;
        margin-right: 7%;
        font-size: 21px;
        color: white;
        width: 400px;
    }


    .days {
        margin-top: 10px;
        font-size: 25px;
        text-align: right;
    }
    @media (max-width: 880px) {
        .days{
            font-size: 20px;
        }
        .phone{
            font-size: 20px;
        }
    }
</style>