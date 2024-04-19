<template>
    <div class="about-services-page">
        <!-- <div class="bg-fader-top"></div>
        <div class="bg-fader-bottom"></div> -->
        <h1 style="z-index: 2;">About our services</h1>

        <div class="service-card-wrapper" style="">
            <div class="service-sheet travel-sheet" elevation="10" style="">
                <h2>Traveling</h2>
                <h4>Kami menyediakan layanan travel ke berbagai kota di Kalimantan dengan harga yang terjangkau</h4>
                <div class="icon-wrapper">
                    <i class="fa-solid fa-car" style="font-size: 1.5rem; color: #c9fffb;"></i>
                </div>
                <img src="../../assets/ball-curve.png" alt="" style="width: 80%; display: flex; justify-self: right;">
            </div>

            <div class="service-sheet cargo-sheet" elevation="10" style="">
                <h2>Cargo</h2>
                <h4 style="transform: translateY(10px);">Kirim barang ke seluruh Kalimantan Timur dengan mudah dan aman bersama BNJ Travel</h4>
                <div class="icon-wrapper" style="transform: translateY(60px);">
                    <i class="fa-solid fa-truck-fast" style="font-size: 1.5rem; color: #e6d9ff;"></i>
                </div>
                <img src="../../assets/ball-sun.png" alt="" style="width: 80%; display: flex; justify-self: right;">
            </div>

            <div class="service-sheet plane-sheet" elevation="10" style="">
                <h2>Tiket Pesawat</h2>
                <h4>Pesan tiket pesawat ke berbagai destinasi dengan mudah dan murah di BNJ Travel</h4>
                <div class="icon-wrapper">
                    <i class="fa-solid fa-plane-up" style="font-size: 1.5rem; color: #ffefe9;"></i>
                </div>
                <img src="../../assets/ball-zig.png" alt="" style="width: 80%; display: flex; justify-self: right;">
            </div>

            <div class="service-sheet ship-sheet" elevation="10" style="">
                <h2>Tiket Kapal</h2>
                <h4>Nikmati kemudahan dan kenyamanan dalam memesan tiket kapal dengan BNJ Travel</h4>
                <div class="icon-wrapper">
                    <i class="fa-solid fa-ship" style="font-size: 1.5rem; color: #ffdbfe;"></i>
                </div>
                <img src="../../assets/ball-prism.png" alt="" style="width: 80%; display: flex; justify-self: right;">
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

<style scoped>

@media screen and (max-width: 576px) {
.service-card-wrapper {
    display: grid;
}
.service-sheet {
    width: 80vw;
}
}

.about-services-page {
    padding: 0 6vw;
    padding-bottom: 150px;
    padding-top: 70px;
    width: 100%; 
    height: fit-content;
    display: grid;
    align-items: center;
    justify-items: center;
    row-gap: 50px;
    color: #FFFFFF;
    /* background-color: #F5F7FE; */
    /* background-image: url(../../assets/images/twin.png);
    background-size: cover;
    background-position: bottom center;
    background-repeat: no-repeat;
    background-attachment: fixed; */
    position: relative;
}

.service-card-wrapper {
    display: flex; 
    justify-content: center; 
    flex-wrap: wrap;
    gap: 30px;
    z-index: 2;
}

.service-sheet {
    /* box-shadow: -3px 3px 10px 1px #ffffff27; */
    display: grid;
    justify-items: left;
    align-items: center;
    padding: 10px 25px;
    border-radius: 10px;
    cursor: pointer;
    width: 300px;
    /* height: 300px; */
    transition: all .3s cubic-bezier(.02,-0.02,0,1);
}
.travel-sheet {
    /* FEEDEC */
    /* 2D7A73 */
    background-color: rgb(51, 60, 83);
    color: #ffffff;
}
.cargo-sheet {
    /* f9ecfe */
    /* 6629DE */
    background-color: rgb(51, 60, 83);
}
.plane-sheet {
    /* ecebf5 */
    /* F0926C */
    background-color: rgb(51, 60, 83);
}
.ship-sheet {
    /* EBFCFF */
    /* B52AB0 */
    background-color:rgb(51, 60, 83);
}
.service-sheet h2 {
    font-size: 1.4rem;
    font-weight: 500;
    margin-bottom: 7px;
    color: #ffffff;
}
.service-sheet h4 {
    line-height: 1.6;
    cursor: text;
    font-weight: 300;
    font-size: .8rem;
    color: #ffffffd0;
    /* text-align: center; */
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
    box-shadow: 0 10px 20px 2px #b6b6b619;
}

.bg-fader-top {
    width: 100vw;
    height: 100vh;
    position: absolute;
    top: 0;
    left: 0;
    background-image: linear-gradient(to top, #ffffff00, #ffffff00, #ffffff00, #ffffff00, #ffffff00, #F5F7FE);
    z-index: 1;
}
.bg-fader-bottom {
    width: 100vw;
    height: 100vh;
    position: absolute;
    bottom: 0;
    left: 0;
    background-image: linear-gradient(to top, #F5F7FE, #ffffff00, #ffffff00, #ffffff00, #ffffff00, #ffffff00);
    z-index: 1;
}

</style>  