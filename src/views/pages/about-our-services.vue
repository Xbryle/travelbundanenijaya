<template>
    <div class="about-services-page">
        <h1>About our services</h1>

        <div class="service-card-wrapper" style="">
            <div class="service-sheet travel-sheet" elevation="10" style="">
                <div class="icon-wrapper">
                    <i class="fa-solid fa-car" style="font-size: 3rem; color: #fd7c75;"></i>
                </div>
                <h2>Traveling</h2>
                <h4>Kami menyediakan layanan travel ke berbagai kota di Kalimantan dengan harga yang terjangkau</h4>
            </div>
            <div class="service-sheet cargo-sheet" elevation="10" style="">
                <div class="icon-wrapper">
                    <i class="fa-solid fa-truck-fast" style="font-size: 3rem; color: #ca46fe;"></i>
                </div>
                <h2>Cargo</h2>
                <h4>Kirim barang ke seluruh Kalimantan Timur dengan mudah dan aman bersama BNJ Travel</h4>
            </div>
            <div class="service-sheet plane-sheet" elevation="10" style="">
                <div class="icon-wrapper">
                    <i class="fa-solid fa-plane-up" style="font-size: 3rem; color: #6453ff;"></i>
                </div>
                <h2>Tiket Pesawat</h2>
                <h4>Pesan tiket pesawat ke berbagai destinasi dengan mudah dan murah di BNJ Travel</h4>
            </div>
            <div class="service-sheet ship-sheet" elevation="10" style="">
                <div class="icon-wrapper">
                    <i class="fa-solid fa-ship" style="font-size: 3rem; color: #29dfff;"></i>
                </div>
                <h2>Tiket Kapal</h2>
                <h4>Nikmati kemudahan dan kenyamanan dalam memesan tiket kapal dengan BNJ Travel</h4>
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


}

.about-services-page {
    padding: 0 6vw;
    width: 100%; 
    height: fit-content;
    display: grid;
    align-items: center;
    justify-items: center;
    row-gap: 50px;
    background-color: #F5F7FE;
    padding: 100px 0;
}

.service-card-wrapper {
    display: flex; 
    justify-content: center; 
    flex-wrap: wrap;
    gap: 30px;
}

.service-sheet {
    box-shadow: 0 5px 20px 2px #b6b6b619;
    display: grid;
    justify-items: left;
    align-items: center;
    padding: 10px 25px;
    border-radius: 10px;
    cursor: pointer;
    width: 280px;
    height: 300px;
    transition: all .3s cubic-bezier(.02,-0.02,0,1);
}
.travel-sheet {
    /* FEEDEC */
    background-color: #FEEDEC;
}
.cargo-sheet {
    /* f9ecfe */
    background-color: #f9ecfe;
}
.plane-sheet {
    /* ecebf5 */
    background-color: #ecebf5;
}
.ship-sheet {
    /* EBFCFF */
    background-color: #EBFCFF;
}
.service-sheet h4 {
    line-height: 1.7;
    cursor: text;
    font-weight: 400;
    font-size: .9rem;
    /* text-align: center; */
}

.icon-wrapper {
    display: flex;
    /* background-color: rgb(242, 242, 242); */
    justify-content: center;
    align-items: center;
    column-gap: 3px;
    margin-bottom: 10px;
    /* width: 90px;
    height: 90px;
    border-radius: 50%; */
}

.service-sheet:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px 2px #b6b6b619;
}

</style>  