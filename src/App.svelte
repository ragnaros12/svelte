<script>
    import Header from "./compnents/Header.svelte";
    import Nav from "./compnents/Nav.svelte";
    import Main from "./compnents/Main.svelte";
    import Usl from "./compnents/Usl.svelte";
    import Clients from "./compnents/Clients.svelte";
    import Acc from "./compnents/Acc.svelte";
    import Why from "./compnents/Why.svelte";
    import Footer from "./compnents/Footer.svelte";

</script>

<Header/>
<Nav/>
<button class="btn-za1 btn-ya">Записаться</button>
<Main/>
<div class="container-icons">
    <div class="bottom-sot">
        <a href="https://www.instagram.com/78_street/" class="icon"><img src="images/inst.png" alt="" ></a>
        <a href="https://wa.me/79110336371" class="icon"><img src="images/whatsapp.svg" alt="" class="icon"></a>
        <a href="https://vk.com/78th.street" class="icon"><img src="images/vk.svg" alt="" class="icon"></a>
        <a href="https://tele.click/Barbershop_78Street" class="icon"><img src="images/telegram.svg" alt="" class="icon"></a>
        <a href="tel:+79110336371" class="icon"><img src="images/phone.svg" alt="" class="icon"></a>
    </div>
</div>
<Usl/>
<Clients/>

<Acc/>
<Why/>
<Footer/>

<style>
    .container-icons{
        position: relative;
        top: -60px;
    }


    .bottom-sot {
        width: 300px;
        height: 60px;
        background: #1e1e1e99;
        display: flex;
        justify-content: space-around;
        margin: auto auto 105px;
    }

    .icon {
        height: 30px;
        margin: auto;
    }
    .icon img{
        height: 100%;
    }


    .btn-za1{
        position: fixed;
        transform: rotate(90deg);
        top: 50%;
        z-index: 200;
        width: 200px;
        height: 50px;
        background: #2b2119;
        font-size: 23px;
        color: white;
        border: none;
        left: -75px;
    }

</style>
