<template>
    <div class="help-page">
        <h1>Bagaimana Kami Bisa</h1>
        <h1 class="cliped-text">Membantu?</h1>
        <p>Kami membantu anda untuk pergi ke tempat tujuan anda dengan mudah seperti pesan tiket pesawat dan kapal. Kami membantu anda dalam membeli tiket pesawat dan kapal dengan mudah dan tanpa mengantri. Tempat pemesanan tiket secara online dan offline yang amanah dan terpercaya. Siap mengantar anda ke tempat tujuan di mana saja di Kalimantan.</p>

        <div class="service-card-wrapper" style="">
            <div class="service-sheet" style="">
                <!-- <i class="fa-solid fa-car" style="font-size: 3rem; color: #FFFFFF;"></i> -->
                <h2>Jasa Pengantaran</h2>
                <i class="fa-solid fa-car"></i>
                <h4>Kami menyediakan layanan perjalanan yang mencakup destinasi di berbagai kota di Kalimantan</h4>
            </div>
            <div class="service-sheet" style="">
                <h2>Kirim Barang</h2>
                <i class="fa-solid fa-truck-fast"></i>
                <h4>Kirim barang ke seluruh Kalimantan dengan mudah dan aman bersama BNJ Travel</h4>
            </div>
            <div class="service-sheet" style="">
                <h2>Tiket Kapal</h2>
                <i class="fa-solid fa-ship"></i>
                <h4>Kami melayani jasa pembelian tiket kapal ke berbagai tempat dan tujuan</h4>
            </div>
            <div class="service-sheet" style="">
                <h2>Tiket Pesawat</h2>
                <i class="fa-solid fa-plane-departure"></i>
                <h4>Beli tiket pesawat ke berbagai destinasi dengan mudah dan murah di BNJ Travel</h4>
            </div>
            <div class="service-sheet" style="">
                <h2>Rental Mobil</h2>
                <i class="fa-solid fa-car-side"></i>
                <h4>Kami menyediakan jasa sewa mobil harian atau per-jam</h4>
            </div>
            <div class="service-sheet" style="">
                <h2>Carter Mobil</h2>
                <i class="fa-solid fa-car-rear"></i>
                <h4>Kami menyediakan jasa carter mobil untuk digunakan dalam waktu sehari maupun beberapa hari</h4>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        components: {
        },
    }
</script>

<style>

.help-page {
    width: 100%;
    padding: 70px 0;
    color: #FFFFFF;
    display: grid;
    justify-items: center;
    /* background-color: #000000; */
    background-image: url(../../assets/images/bg3.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: top right;
    background-attachment: fixed;
}
.help-page h1{
    font-size: calc(1vw + 1.7rem);
    line-height: 1.2;
    text-align: center
}
.help-page p {
    text-align: center;
    font-size: .95rem;
    font-weight: 300;
    margin-bottom: 70px;
    color: #ffffffbe;
    max-width: 50vw;
}
.help-page .cliped-text {
    color: transparent;
    background-image: none;
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-stroke-width: 1px;
    -webkit-text-stroke-color: #ffffffd3;
    margin-bottom: 30px;
}
.help-page a {
    display: flex;
    text-decoration: none;
    text-transform: none;
    align-items: center;
    gap: 5px;
    font-size: .7rem;
    margin-top: 20px;
    font-weight: 300;
    letter-spacing: 1px;
}

.help-page a span {
    border-bottom: 1px solid #FFFFFF;
}
.service-card-wrapper {
    display: flex; 
    overflow-x: auto;
    overflow-y: hidden;
    gap: 30px;
    z-index: 2;
    width: 65vw;
    padding: 20px 20px;
}


.service-sheet {
    /* box-shadow: -3px 3px 10px 1px #ffffff27; */
    display: grid;
    justify-items: center;
    align-items: center;
    padding: 15px 25px;
    border-radius: 10px;
    cursor: pointer;
    width: 300px;
    min-width: 300px;
    box-sizing: border-box;
    /* height: 300px; */
    transition: all .3s cubic-bezier(.02,-0.02,0,1);
    -webkit-overflow-scrolling: touch;
    /* box-shadow: 0 0px 20px 3px #ffffffa2; */
    border: 1px solid #ffffffa2;
}

.service-sheet h2 {
    font-size: 1.9rem;
    font-weight: 500;
    margin-bottom: 40px;
    text-align: center;
    color: #ffffff;
    font-family: Oswald;
    text-transform: uppercase;
    line-height: 1;
    cursor: pointer;
}
.service-sheet i {
    font-size: 90px;
    margin-bottom: 20px
}
.service-sheet h4 {
    line-height: 1.6;
    cursor: text;
    font-weight: 300;
    font-size: .9rem;
    color: #ffffffd0;
    text-align: center;
    /* text-align: center; */
    cursor: pointer;
}

.icon-wrapper {
    display: flex;
    background-color: #ffffff44;
    justify-content: crgba(255, 255, 255, 0.259)r;
    align-items: center;
    justify-content: center;
    column-gap: 3px;
    margin-bottom: 10px;
    width: 45px;
    height: 45px;
    border-radius: 50%;
    transform: translateY(40px);
}

.service-sheet:hover {
    transform: translateY(-5px);
    box-shadow: 0 0px 20px 3px #ffffffa2;
}

@media screen and (max-width: 576px) {
.service-card-wrapper {
    /* display: grid; */
    width: 80vw;
    padding: 20px 0px;
}
.service-sheet {
    min-width: 80vw;
    width: 70vw;
}
.help-page p {
    max-width: 80vw;
}
}

</style>