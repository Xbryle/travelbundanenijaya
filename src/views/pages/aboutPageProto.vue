<template>
    <div class="about-page">
        <div class="images-about">
            <div class="left-section">
                <img src="../../assets/barinmap.jpg" alt="" style="max-width: 40vw;">
                <div>
                    <h2>01</h2>
                    <p>Happy Clients</p>
                </div>
            </div>
            <div class="right-section">
                <img class="img1" src="../../assets/banner.png" alt="" style="max-width: 40vw;">
                <img class="img2" src="../../assets/idea.jpg" alt="" style="max-width: 40vw;">
            </div>
        </div>
        <div class="words-about">
            <h4>Tentang Kami</h4>
            <h1>Pesan Tiket dan Traveling,<br>Nikmati <span>Petualangan Anda!</span></h1>
            <p><span>BNJ</span> didirikan pada tahun 2020 dan telah berkembang pesat menjadi travel terpercaya dengan reputasi gemilang. Kami berkomitmen untuk membantu Anda dalam berbagai kebutuhan perjalanan, baik untuk berpergian, mengantar barang, ataupun memesan tiket pesawat dan kapal.</p>
            <ul>
                <li>Ui yang indah dan mudah dipahami, animasi profesional</li>
                <li>Keunggulan ini adalah design piksel yang sempurna & kode yang jelas dikirimkan</li>
                <li>Hardikan layanan anda dengan felskibel, nyaman dan serbaguna</li>
            </ul>
            <a href="https://api.whatsapp.com/send/?phone=6285161319636&text=Halo+Min%21+saya+minta+Info+Tiket+Kapal%3F&type=phone_number&app_absent=0" target="_blank">
                <v-btn class="contact-about">Hubungi Kami <i class="fa-brands fa-whatsapp ms-2" style="color: lightgreen; font-size: 1.4rem;"></i></v-btn>
            </a>
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

.about-page {
    padding: 70px 5%;
    width: 100vw; 
    justify-content: center;
    gap: 40px;
    color: #000000;
    background-color: #ffffff;
    display: flex;
    /* flex-wrap: wrap; */
    box-sizing: border-box;
}

.images-about {
    display: flex;
    gap: 40px;
    justify-content: center;
}
.images-about .left-section {
    display: grid;
    width: fit-content;
}
.images-about .left-section img {
    width: 200px;
    display: flex;
    align-self: end;
    border-radius: 15px;
    aspect-ratio: 1/1;
    margin-bottom: -70px;
}
.images-about .left-section div {
    display: grid;
    align-self: flex-end;
    width: fit-content;
    height: fit-content;
}
.images-about .left-section div h2 {
    font-size: 1.9rem;
    margin-left: 20px;
}
.images-about .left-section div p {
    display: flex;
    align-items: center;
    font-size: .9rem;
    font-weight: 400;
    column-gap: 5px;
    line-height: 1;
    margin-bottom: 0;
}
.images-about .left-section div p::before {
    content: "";
    /* display: flex; */
    width: 15px;
    height: 2px;
    border-radius: 5px;
    background-color: #000000;
}


.images-about .right-section {
    display: grid;
    justify-content: start;
    align-content: center;
    gap: 40px;
}

.images-about .right-section .img1 {
    width: 290px;
    display: grid;
    align-self: center;
    border-radius: 15px;
    aspect-ratio: 1.2/1;
}
.images-about .right-section .img2 {
    width: 200px;
    display: grid;
    align-self: center;
    border-radius: 15px;
    aspect-ratio: 1/1;
}


.words-about {
    display: grid;
    width: 40vw;
    align-content: end;
    gap: 30px;
}
.words-about h4 {
    font-size: 1rem;
    font-weight: 500;
    margin-bottom: 0;
    line-height: 1;
} 
.words-about h1 {
    font-size: calc(2vw + 1rem);
    font-weight: 800;
    line-height: 1.1;
    margin-bottom: 0;
} 
.words-about h1 span {
    color: transparent;
    -webkit-text-stroke-width: 1px;
    -webkit-text-stroke-color: #000000;
    background-clip: text;
} 
.words-about p {
    margin-bottom: 0;
} 
.words-about p span {
    font-weight: 700;
} 
.words-about .contact-about {
    background-color: #000000;
    border-radius: 10px solid #ffffff; 
    color: #ffffff; 
    box-shadow: transparent;
    width: fit-content; 
    text-transform: none; 
    padding: 20px; 
    border-radius: 30px; 
    font-size: .9rem; 
    font-weight: 400;
    letter-spacing: 1px;
} 


@media screen and (max-width: 1024px) {

}
@media screen and (max-width: 1000px) {
    .images-about {
        display: grid;
        grid-template-areas: 'top' 'bottom';
        align-content: start;
    }


    .images-about .left-section {
        grid-area: bottom;
        height: 100%;
    }
    .images-about .left-section img {
        margin-bottom: 50px;
    }


    .images-about .right-section {
        grid-area: top;
        align-content: start;
        height: fit-content;
    }


    .images-about .right-section .img2 {
        display: none;
    }
}

@media only screen and (max-width: 1024px) and (max-height: 1368px) and (min-height: 1024px) {

}


@media screen and (max-width: 630px) {
    .about-page {
        display: grid;
        justify-content: center;
        padding: 70px 20px;
        box-sizing: border-box;
    }

    .images-about {
        display: flex;
        align-content: start;
        max-width: none;
        margin-bottom: 20px;
    }


    .images-about .left-section {
        grid-area: bottom;
    }
    .images-about .left-section img {
        margin-bottom: 0;
    }


    .images-about .right-section {
        grid-area: top;
        align-content: start;
        height: fit-content;
    }


    .images-about .right-section .img2 {
        display: grid;
    }

    .words-about {
        display: grid;
        width: 100%;
        align-content: start;
        justify-content: center;
    }
    .words-about p {
        text-align: justify;
        font-size: .9rem;
    }
    .words-about ul li {
        font-size: .9rem;
    }
    .words-about h4 {
        text-align: center;
    }
    .words-about h1 {
        text-align: center;
    }

}

</style>  