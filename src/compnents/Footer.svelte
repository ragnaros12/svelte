<footer class="container bg">
    <div class="footer-container">
        <a name="contacts" class="contact-title">Контакты</a>
        <div class="container-messengers">
            <div class="container-items">
                <div class="container-images">
                    <img src="images/phone1.svg" class="image-messenger" alt="">
                    <img src="images/location.svg" class="image-messenger" alt="">
                    <img src="images/email.svg" class="image-messenger" alt="">
                    <img src="images/time.svg" class="image-messenger" alt="">
                </div>
                <div class="container-texts">
                    <div class="container-data-messenger">
                        <div class="title-messenger">Телефон</div>
                        <div class="subtitle-messenger">+7 (911) 033-63-71</div>
                    </div>
                    <div class="container-data-messenger">
                        <div class="title-messenger">Адрес</div>
                        <div class="subtitle-messenger">Свеаборгская улица, 27, Санкт-Петербург</div>
                    </div>
                    <div class="container-data-messenger">
                        <div class="title-messenger">Почта</div>
                        <div class="subtitle-messenger">barbershop78thstreet@yandex.ru</div>
                    </div>
                    <div class="container-data-messenger">
                        <div class="title-messenger">Время работы</div>
                        <div class="subtitle-messenger">Ежедневно с 10:00-22:00</div>
                    </div>
                </div>
            </div>
            <div class="container-items">
                <div style="position:relative;overflow:hidden;"><a
                        href="https://yandex.ru/maps/2/saint-petersburg/?utm_medium=mapframe&utm_source=maps"
                        style="color:#eee;font-size:12px;position:absolute;top:0px;">Санкт‑Петербург</a><a
                        href="https://yandex.ru/maps/2/saint-petersburg/house/sveaborgskaya_ulitsa_27/Z0kYdQRhQEEPQFtjfXR2c3hlYg==/?ll=30.331948%2C59.872466&utm_medium=mapframe&utm_source=maps&z=16"
                        style="color:#eee;font-size:12px;position:absolute;top:14px;">Свеаборгская улица, 27 на карте
                    Санкт‑Петербурга, ближайшее метро Парк Победы — Яндекс Карты</a>
                    <iframe src="https://yandex.ru/map-widget/v1/-/CCURUDEPoB" width="474" height="430" frameborder="1"
                            allowfullscreen="true" style="position:relative;"></iframe>
                </div>
            </div>
        </div>
        <div class="messengers">
            <img src="images/inst.png" alt="" class="icon icon-footer">
            <img src="images/whatsapp.svg" alt="" class="icon icon-footer">
            <img src="images/vk.svg" alt="" class="icon icon-footer">
            <img src="images/telegram.svg" alt="" class="icon icon-footer">
        </div>

    </div>
</footer>

<style>
    .bg{
        background: url("../images/bg-footer.png") center center/cover no-repeat;
        width: 100%;
    }
    .footer-container{
        width: 75%;
        margin: 50px auto;
        display: flex;
        flex-direction: column;
        background: #1e1e1e99;
    }

    .contact-title{
        font-size: 50px;
        margin-left: auto;
        margin-right: auto;
        margin-top: 40px;
        color: white;
    }
    .container-messengers{
        width: 100%;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
        height: 100%;
    }
    .messengers{
        width: 300px;
        margin-left: auto;
        height: 80px;
        margin-bottom: 10px;
        margin-right: 40px;
        display: flex;
        justify-content: space-between;
    }
    .icon-footer{
        height: 40px;
        width: 40px;
    }
    .container-items{
        width: 450px;
        display: flex;
        flex-direction: initial;
        height: 435px;
    }
    .container-items:first-child{
        width: initial;
        display: flex;
    }
    .container-items:last-child{
        width: 350px;
        height: 350px;
        margin-top: auto;
        margin-bottom: auto;
        background: white;
    }
    .container-images{
        display: flex;
        width: 60px;
        flex-direction: column;
        justify-content: space-around;
        height: 100%;
    }

    .container-data-messenger{
        display: flex;
        flex-direction: column;
    }
    .title-messenger{
        font-size: 35px;
        color: white;
    }

    .subtitle-messenger{
        font-size: 25px;
        color: white;
    }
    .container-texts{
        display: flex;
        margin-left: 20px;
        flex-direction: column;
        justify-content: space-around;
        height: 100%;
    }
    .image-messenger{
        height: 40px;
        margin-top: auto;
        margin-bottom: auto;
    }

    @media (max-width: 1260px) {
        .title-messenger{
            font-size: 27px;
        }
        .subtitle-messenger{
            font-size: 20px;
        }
    }
    @media (max-width: 1127px) {
        .messengers{
            margin-right: auto;
            margin-left: auto;
        }
    }
    @media (max-width: 695px) {
        .image-messenger{
            height: 25px;
        }
        .title-messenger{
            font-size: 20px;
        }
        .subtitle-messenger{
            font-size: 13px;
        }
        .icon-footer{
            height: 25px;
            width: 25px;
        }
    }

    @media (max-width: 530px) {
        .footer-container{
            width: 85%;
        }
        .contact-title{
            font-size: 35px;
        }
    }
    @media (max-width: 451px) {
        .container-items:last-child{
            width: 200px;
            height: 200px;
        }
    }


</style>