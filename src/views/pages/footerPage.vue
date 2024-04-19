<template>
    <div class="footer-page">
        
        <div class="left-section">
            <p>we are ready to do this</p>
            <h1>Let's get in<br>Touch</h1>
            <a href="https://api.whatsapp.com/send/?phone=6285161319636&text=Halo+Min%21+saya+minta+Info+Tiket+Kapal%3F&type=phone_number&app_absent=0" target="_blank">
                <button class="button-57" role="button"><span class="text">Hubungi Kami <i class="fa-solid fa-arrow-right ms-1"></i></span><span>Whatsapp</span></button>
            </a>
        </div>

        <div class="right-section">
            <div class="flex">
                <div class="halaman">
                    <h3>Halaman</h3>
                    <div class="p-wrapper">
                        <p>General Data Protection</p>
                        <p>Syarat dan Ketentuan</p>
                        <p>Kebijakan Privasi</p>
                    </div>
                </div>
                <div class="contact">
                    <h3>Kontak</h3>
                    <div class="contact-wrapper">
                        <div>
                            <i class="fa-solid fa-phone" style="font-size: .8rem;"></i>
                            <a>082255127027</a>
                        </div>
                        <div class="mb-1">
                            <a>cvbundanenijayatourtravel@gmail.com</a>
                        </div>
                        <!-- <div>
                            <i class="fa-solid fa-phone"></i>
                            <a>085161319636</a>
                        </div> -->
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
                    </div>
                </div>
            </div>
            <p style="text-align: center;">copyright &copy;2024 <span>BNJ Travel.</span> designed by <span>MC Project</span></p>
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

.footer-page {
    width: 100%;
    background-color: #000000;
    color: #FFFFFF;
    padding: 50px 7%;
    display: flex;
    flex-wrap: wrap;
    row-gap: 100px;
    flex-direction: wrap;
    justify-content: space-around;
}

.footer-page .right-section {
    display: grid;
    gap: 70px;
    width: fit-content;
}

.footer-page .right-section .contact {
    display: grid;
    align-content: space-between;
    height: 150px;
    width: fit-content;
}
.footer-page .right-section .contact h3 {
    font-size: 1.5rem;
    font-weight: 600;
    line-height: 1;
}
.footer-page .right-section .contact-wrapper {
    display: grid;
    gap: 10px;
}
.footer-page .right-section .contact-wrapper div{
    display: flex;
    gap: 5px;
    align-items: center;
    justify-content: start;
}
.footer-page .right-section .contact-wrapper div a{
    color: #b7b7b7;
    text-decoration: none;
    font-weight: 400;
    font-size: .9rem;
}

.footer-page .right-section .halaman {
    display: grid;
    align-content: space-between;
    height: 150px;
}

.footer-page .right-section .halaman h3 {
    font-size: 1.5rem;
    font-weight: 600;
    line-height: 1;
}
.footer-page .right-section .halaman .p-wrapper {
    display: grid;
    gap: 10px;
}
.footer-page .right-section .halaman .p-wrapper p {
    font-size: .9rem;
    margin-bottom: 0;
    font-weight: 400;
    color: #b7b7b7;
}

.footer-page .right-section p {
    font-size: .9rem;
    color: #b7b7b7;
    font-weight: 400;
}
.footer-page .right-section p span {
    color: #ffffff;
}



.footer-page .left-section {
    display: grid;
    justify-items: center;
    width: fit-content;
}
.footer-page .left-section h1 {
    font-weight: 600;
    font-size: calc(2vw + 2.2rem);
    text-align: center;
    line-height: 1;
    margin-bottom: 40px;
}

.footer-page .left-section p {
    text-transform: uppercase;
    font-size: .7rem;
    font-weight: 500;
    letter-spacing: 2px;
    margin-bottom: 25px;
}

.footer-page .right-section .flex {
    display: flex;
    gap: 100px;
}

@media screen and (max-width: 576px) {
    .footer-page .right-section .flex {
        gap: 40px;
        display: grid;
        justify-items: center;
    }
    .footer-page .right-section .contact {
        width: 100%;
        justify-items: center;
        height: 135px;
    }
    .footer-page .right-section .contact h3 {
        text-align: center;
    }
    .footer-page .right-section .contact .contact-wrapper {
        justify-items: center;
    }
    .footer-page .right-section .halaman {
        width: 100%;
        justify-items: center;
        height: 135px;
    }
    .footer-page .right-section .halaman h3, .footer-page .right-section .halaman p {
        text-align: center;
    }
    .footer-page .right-section p {
        font-size: .8rem;
    }
    .footer-page .right-section {
        justify-items: center;
    }
    .footer-page .right-section .halaman .p-wrapper p {
        font-size: .8rem;
    }
    .footer-page .right-section .halaman h3, .footer-page .right-section .contact h3 {
        font-size: 1.3rem;
    }
    .footer-page .right-section .contact-wrapper div a{
        font-size: .8rem;
        text-align: center
    }
}


/* CSS */
.button-57 {
  position: relative;
  overflow: hidden;
  border: 1px solid #ffffff;
  color: #FFFFFF;
  display: inline-block;
  font-size: 15px;
  line-height: 15px;
  padding: 15px 18px 17px;
  text-decoration: none;
  cursor: pointer;
  background: transparent;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  border-radius: 30px;
  transition: all .7s cubic-bezier(0.48, 0, 0.12, 1);
  align-items: center;
  width: 200px;
}

.button-57 span:first-child {
  position: relative;
  transition: color 600ms cubic-bezier(0.48, 0, 0.12, 1);
  z-index: 10;
}

.button-57 span:last-child {
  color: #000000;
  display: block;
  position: absolute;
  bottom: 0;
  transition: all 500ms cubic-bezier(0.48, 0, 0.12, 1);
  z-index: 100;
  opacity: 0;
  top: 50%;
  left: 50%;
  transform: translateY(225%) translateX(-50%);
  height: 14px;
  line-height: 13px;
}

.button-57:after {
  content: "";
  position: absolute;
  bottom: -50%;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: #FFFFFF;
  transform-origin: bottom center;
  transition: transform 600ms cubic-bezier(0.48, 0, 0.12, 1);
  transform: skewY(9.3deg) scaleY(0);
  z-index: 50;
}

.button-57:hover {
    box-shadow: 0 0 20px 2px #ffffff85;
    border: 1px solid #000000;
}

.button-57:hover:after {
  transform-origin: bottom center;
  transform: skewY(9.3deg) scaleY(2);
}

.button-57:hover span:last-child {
  transform: translateX(-50%) translateY(-100%);
  opacity: 1;
  transition: all 900ms cubic-bezier(0.48, 0, 0.12, 1);
}









.footer-page .contact-media {
    /* background-color: rgba(13, 0, 255, 0.188); */
    display: flex;
    align-items: flex-start;
}
.footer-page .contact-media a {
    position: relative;
    color: #FFFFFF;
    text-decoration: none;
    width: 25px;
    height: 25px;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
    border: 1px solid #FFFFFF;
    border-radius: 50%;
}
.footer-page .contact-media a i {
    z-index: 1;
}
.footer-page .contact-media a div{
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

.footer-page .contact-media a:hover div {
    scale: 1;
}

</style>