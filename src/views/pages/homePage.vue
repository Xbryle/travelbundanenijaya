<template>
  <div style="position: relative;">
    <!-- <img class="decor-svg-home decor-left" src="../../assets/left-svg.png" alt="">
    <img class="decor-svg-home decor-right" src="../../assets/right-svg.png" alt=""> -->
    <!-- <div class="bg-fader"></div> -->
    <!-- <div class="box-brand-animation">
      <a class="brand-animation" style="color: #000000a9">
        B
        <span></span>
        <span></span>
        <span></span>
        <span></span>
      </a>
      <a class="brand-animation" style="color: #000000a9">
        N
        <span></span>
        <span></span>
        <span></span>
      </a>
      <a class="brand-animation" style="color: #000000a9">
        J
        <span></span>
        <span></span>
        <span></span>
      </a>
    </div> -->

    <div class="home-page" id="home-page">
      <nav>
        <v-btn
            icon
            class="menu"
          >
            <v-icon style="color: lightgreen;">fa-brands fa-whatsapp</v-icon>
        </v-btn>
      </nav>
          <div class="brand-box">
            <h1 class="tittle-texts"><span>TRAVEL </span>BNJ
              <div></div>
              <div></div>
              <div></div>
              <div></div>
            </h1>
          </div>

          <div class="home-about">
            <h4>#BIT ABOUT US</h4>
            <p>Tepmatnya pemesanan tiket terpercaya <br> tiket pesawat dan tiket kapal  <br>bepergian melalui jalur darat</p>
            <p>Ke seluruh daerah Kalimantan!!! <br> Travel BNJ</p>
          </div>
          
          <div class="sosmed-box">
            <div class="sosmed">
              <a href="#" target="_blank"><i class="fa-brands fa-facebook-f" style="color: #FFFFFF;"></i></a>
              <a href=""><i class="fa-brands fa-whatsapp" style="color: #FFFFFF;"></i></a>
            </div>
            <div class="bottom-line"></div>
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

@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Barlow+Condensed:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

/* ===============================================Home===================================================== */

.home-page {
    width: 100vw;
    height: 103vh;
    color: rgb(255, 255, 255);
    box-sizing: border-box;
    overflow: visible;
    position: relative;
    display: grid;
    justify-content: center;
    /* background-image: url(../../assets/images/steer.png);
    background-size: cover;
    background-position: bottom right;
    background-repeat: no-repeat; */
    /* background-image: linear-gradient(to bottom right, #F3F0FF, #F0F6FF); */
    /* background-color: #00000059; */
    /* background-blend-mode: overlay; */
    /* z-index: 100; */
    /* background-color: #222A36; */

    /* background-image: url(../../assets/images/gradient.png); */
    /* background-image: linear-gradient(to right, #10131D,#151927,#1F2334,#4a3a4f); */
    /* background-size: cover;
    background-position: bottom left;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-color: #0000002e;
    background-blend-mode: overlay; */
    /* background-color: #ffffff76;
    background-blend-mode: overlay; */
}


/* ================nav */


nav {
    width: max-content;
    height: max-content;
    position: fixed;
    display: grid;
    justify-items: right;
    right: 7%;
    top: 5%;
    z-index: 100;
}

nav .menu {
    width: 50px;
    height: 50px;
    display: grid;
    align-items: center;
    justify-items: right;
    cursor: pointer;
    margin-bottom: 10px;
    position: relative;
}

/* =========intro-box */

.home-about {
    width: max-content;
    height: max-content;
    display: grid;
    position: absolute;
    gap: 5px;
    bottom: 10%;
    left: 5%;
    z-index: 2;
}
.home-about h4 {
    font-weight: 550;
    letter-spacing: 3px;
    font-size: 12px;
}
.home-about p {
    font-family: 'Poppins';
    font-size: 12px;
    font-weight: 200;
    color: #ffffffc1;
    line-height: 2.1;
}
.home-about p:nth-child(2) {
    margin-bottom: 10px;
}
.home-about p:nth-child(3) {
    word-spacing: 5px;
}



/* =========home-sosmed */

.sosmed-box {
    display: grid;
    box-sizing: border-box;
    width: max-content;
    height: max-content;
    position: absolute;
    column-gap: 5px;
    bottom: 5%;
    left: 5%;
    z-index: 2;
}
.sosmed {
    display: flex;
    column-gap: 10px;
}
.sosmed-box .bottom-line {
    width: 100%;
    height: .5px;
    border-radius: 10px;
    background-color: #ffffff8e;
}



/* =============================intro */

.home-page .tittle-texts {
    position: relative;
    font-size: calc(2vw + 6em);
    color: #ffffff;
    line-height: .8;
    margin-bottom: 7px;
    font-weight: 600;
    font-family: 'Barlow Condensed';
    letter-spacing: 1px;
    word-spacing: 1px;
    z-index: 2;
}
.home-page .tittle-texts span {
    color: transparent;
    background-image: none;
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-stroke-width: 1px;
    -webkit-text-stroke-color: #ffffff;
}

.home-page .tittle-texts div:nth-child(2) {
    background-color: #ffffff;
    position: absolute;
    width: 23%;
    height: 1px;
    left: 5%;
    bottom: -18%;
}
.home-page .tittle-texts div:nth-child(2):after {
    content: "BUNDA NENI JAYA";
    width: max-content;
    height: fit-content;
    position: relative;
    display: grid;
    align-self: center;
    font-size: calc(.1vw + .09em);
    font-family: 'poppins';
    letter-spacing: 7px;
    text-transform: uppercase;
    color: #ffffffd1;
    top: -350%;
    left: 115%;
    font-weight: 300;
}
.home-page .tittle-texts div:nth-child(3) {
    background-color: #ffffff;
    position: absolute;
    width: 24%;
    height: 1px;
    right: 4%;
    bottom: -18%;
}
.home-page .tittle-texts div:nth-child(4) {
    width: 1px;
    height: 19%;
    background-color: #ffffff;
    position: absolute;
    bottom: -18%;
    left: 5%;
}
.home-page .tittle-texts div:nth-child(5) {
    width: 1px;
    height: 20%;
    background-color: #ffffff;
    position: absolute;
    bottom: -17%;
    right: 4%;
    font-size: .8em;
    font-family: 'poppins';
}

/* ===================================== */
.brand-box {
    width: max-content;
    display: grid;
    justify-items: center;
    align-content: center;
    padding: 0px;
    position: relative;
}

/* media screen */
@media screen and (max-width: 1024px) {

    .brand-box {
        padding-left: 50px;
    }
    .brand-box .read-more {
        display: none;
    }

}

@media only screen and (max-width: 1024px) and (max-height: 1368px) and (min-height: 1024px) {

}


@media screen and (max-width: 576px) {
    
    .home-page .tittle-texts {
        font-size: calc(2vw + 4.5em);
    }
    .brand-box {
        padding-right: 0;
        padding-left: 0;
    }

    .home-page .tittle-texts div:nth-child(2) {
        width: 23%;
        height: 1px;
        left: 5.3%;
        bottom: -18%;
    }
    .home-page .tittle-texts div:nth-child(2):after {
        font-size: calc(.1vw + .06em);
        top: -150%;
        left: 107%;
    }
    .home-page .tittle-texts div:nth-child(3) {
        content: "";
        width: 23%;
        height: 1px;
        right: 4%;
        bottom: -17%;
    }
    .home-page .tittle-texts div:nth-child(4) {
        width: 1px;
        height: 19%;
        bottom: -18%;
        left: 5%;
    }
    .home-page .tittle-texts div:nth-child(5) {
        width: 1px;
        height: 20%;
        bottom: -17%;
        right: 3.8%;
    }



    .home-about h4 {
        font-size: 10px;
    }
    .home-about p {
        font-size: 10px;
    }
}



.box-brand-animation {
    width: 180px;
    height: 48vh;
    display: flex;
    justify-content: space-between;
    top: 3%;
    left: 5%;
    position: absolute;
    overflow: visible;
    z-index: 101;
}

a.brand-animation {
    height: inherit;
    display: grid;
    position: relative;
    align-content: center;
    justify-items: center;
    font-size: 23px;
    overflow: hidden;
    color: #000000a9;
}


a.brand-animation:nth-child(1) {
    height: 100%;
    overflow: visible;
}
a.brand-animation:nth-child(1) span:nth-child(1) {
    opacity: 0;
}
a.brand-animation:nth-child(1) span:nth-child(4) {
    position: absolute;
    width: 1px;
    height: 100%;
    background-color: #00000028;
    overflow: visible;
}


a.brand-animation span:nth-child(1) {
    width: 1px;
    height: 100%;
    background-color: #00000028;
    position: absolute;
}
a.brand-animation span:nth-child(2) {
    width: 5px;
    height: 5px;
    background-color: #00000028;
    border-radius: 50%;
    position: absolute;
    opacity: 1;
}





a.brand-animation:nth-child(1) span:nth-child(2) {
    top: 10%;
}
a.brand-animation:nth-child(2) span:nth-child(2) {
    bottom: 20%;
}
a.brand-animation:nth-child(3) span:nth-child(2) {
    top: 30%;
}
a.brand-animation:nth-child(4) span:nth-child(2) {
    top: 15%;
}
a.brand-animation:nth-child(5) span:nth-child(2) {
    bottom: 30%;
}





a.brand-animation span:nth-child(3) {
    position: absolute;
}

@media screen and (max-width: 576px) {
    .box-brand-animation {
        top: 0;
        left: 3%;
        width: 70px;
        height: 35vh;
        display: none;
    }
    a.brand-animation {
        font-size: 7px;
    }
    .decor-svg-home {
        width: 70vw;
        display: none;
    }
    /* .home-page {
        background-image: url(../../assets/images/gradient.png);
        background-size: cover;
        background-position: bottom left;
        background-repeat: no-repeat;
        background-attachment: fixed;
    } */
}


.decor-svg-home {
    position: absolute;
    height: 90vh;
    z-index: 1;
}
.decor-right {
    right: 0;
    bottom: 0;
}
.decor-left {
    left: 0;
    bottom: 0;
}
.bg-fader {
    width: 100vw;
    height: 30vh;
    position: absolute;
    bottom: 0;
    left: 0;
    background-image: linear-gradient(to top, #f5f7fe, #ffffff00, #ffffff00, #ffffff00, #ffffff00, #ffffff00, #ffffff00, #ffffff00, #ffffff00, #ffffff00);
    z-index: 1;
}

</style>  