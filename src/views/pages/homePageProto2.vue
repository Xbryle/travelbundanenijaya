<template>
    <section id="home">
        <nav>
            <img src="../../assets/bnj.png" alt="">
        </nav>

        <div class="content">
            <h1>Anda sedang ingin<br><span>Pergi Keluar Kota?</span>
            </h1>
            <p>Kami menyediakan layanan perjalanan yang mencakup destinasi di  berbagai kota di Kalimantan. Kami berkomitmen untuk memberikan pengalaman perjalanan yang menyenangkan dan nyaman bagi pelanggan kami.</p>
            <a class="contact-us" target="_blank" href="https://api.whatsapp.com/send/?phone=6285161319636&text=Halo+Min%21+saya+minta+Info+Tiket+Kapal%3F&type=phone_number&app_absent=0">
                Hubungi Kami <i class="fa-solid fa-arrow-right"></i>
            </a>
        </div>
        <div class="contact-media">
            <a class="facebook" target="_blank" href="https://www.google.com/url?q=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D100090906154171%26mibextid%3DZbWKwL&sa=D&sntz=1&usg=AOvVaw3e7Qk87HR-KFWI6poiAiop" style="font-size: .7rem;">
                <div></div>
                <i class="fa-brands fa-facebook-f"></i>
            </a>
            <a class="whatsapp ms-2" href="https://api.whatsapp.com/send/?phone=6285161319636&text=Halo+Min%21+saya+minta+Info+Tiket+Kapal%3F&type=phone_number&app_absent=0" style="font-size: .8rem;" target="_blank">
                <div></div>
                <i class="fa-brands fa-whatsapp"></i>
            </a>
            <a class="instagram ms-2" href="https://www.google.com/url?q=https%3A%2F%2Fwww.instagram.com%2Fcv_bunda_neni_jaya_travel&sa=D&sntz=1&usg=AOvVaw3joCXKYGhZm55_9bo8oibU" style="font-size: .8rem;" target="_blank">
                <div></div>
                <i class="fa-brands fa-instagram"></i>
            </a>
        </div>
    </section>
</template>

<script>

export default {
    components: {
    },
    mounted() {
    
}
}

</script>
  
<style scoped>
  
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Barlow+Condensed:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&family=Poppins:wght@100;200;300;500;600;700&display=swap');

/* ===============================================Home===================================================== */

#home {
    width: 100vw;
    height: 100vh;
    position: relative;
    display: grid;
    background-image: url(../../assets/images/Frame\ 3.png);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: bottom right;
    background-attachment: fixed;
    color: #FFFFFF;
    box-sizing: border-box;
}

#home nav {
    /* background-color: rgba(0, 255, 255, 0.179); */
    padding: 20px 0 20px 50px;
    width: 100%;
}
#home nav img {
    width: 250px;
    cursor: pointer;
}

#home .content {
    /* background-color: rgba(0, 255, 153, 0.137); */
    padding: 0 15%;
    display: grid;
    align-content: center;
}

#home .content h1{
    font-size: calc(3vw + 2rem);
    line-height: 1;
}
#home .content h1 span{
    color: transparent;
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-stroke-width: 1px;
    -webkit-text-stroke-color: #ffffff;
}
#home .content p{
    width: 32vw;
    font-size: .9rem;
    font-weight: 300;
    margin-top: 30px;
    margin-bottom: 30px;
}

#home .content .contact-us{
    width: fit-content;
    font-size: .9rem;
    font-weight: 300;
    color: #FFFFFF;
    text-decoration: none;
    padding: 10px 15px;
    border: 1px solid #ffffffa7;
    border-radius: 40px;
    display: flex;
    align-items: center;
    gap: 5px;
    background-image: linear-gradient(to right, #7b5332b7, #7b53324b);
    background-size: contain;
    background-repeat: no-repeat;
    background-position-x: -140px;
    transition: all .4s cubic-bezier(.02,-0.02,0,1);
}
#home .content .contact-us:hover {
    background-position-x: 0;
}

#home .contact-media {
    /* background-color: rgba(13, 0, 255, 0.188); */
    padding: 0 0px 20px 50px;
    display: flex;
    align-items: flex-end;
    gap: 10px;
}
#home .contact-media a {
    position: relative;
    color: #FFFFFF;
    text-decoration: none;
    width: 30px;
    height: 30px;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
    border: 1px solid #FFFFFF;
    border-radius: 50%;
}
#home .contact-media a i {
    z-index: 1;
}
#home .contact-media a div{
    position: absolute;
    display: flex;
    justify-self: center;
    align-self: center;
    width: inherit;
    height: inherit;
    border-radius: 50%;
    background-color: #5a5a5aa2;
    transition: all .4s cubic-bezier(.02,-0.02,0,1);
    z-index: 0;
    scale: 0;
}

#home .contact-media a:hover div {
    scale: 1;
}
@media screen and (max-width: 1024px) {
    #home .content p{
        width: 50vw;
    }
    #home {
        background-position: bottom center;
    }
}
@media screen and (max-width: 576px) {
    #home .content h1{
        font-size: calc(1.4vw + 1.7rem);
    }
    #home .content p{
        width: 60vw;
        font-size: 1rem
    }
    #home {
        background-position: bottom center;
    }
    #home nav img {
        width: 50vw;
    }
}
@media screen and (max-width: 376px) {
    #home .content h1{
        font-size: calc(1.4vw + 1.5rem);
    }
    #home .content p{
        font-size: 1rem
    }
}
@media screen and (max-width: 611px) {
    #home .content p{
        font-size: .9rem
    }
}
@media screen and (max-width: 321px) {
    #home nav h1 {
        font-size: 1.2rem;
    }
    #home .content h1{
        font-size: calc(1.4vw + 1.4rem);
    }
    #home .content p{
        width: 60vw;
        font-size: .7rem
    }
}
</style>  