<template>
    <div class="about-page">
        <div class="card-about">
            <div class="image-about">
                <img src="../../assets/beach.jpg" alt="">
            </div>
            <div class="words-about">
                <h3>About Us</h3>
                <p>BNJ didirikan pada tahun 2020 dan telah berkembang pesat menjadi travel terpercaya dengan reputasi gemilang. Kami berkomitmen untuk membantu Anda dalam berbagai kebutuhan perjalanan, baik untuk berpergian, mengantar barang, ataupun memesan tiket pesawat dan kapal.</p>
                <div class="rainbow">
                    <v-btn style="background-color: #000000; color: #ffffff; width: fit-content; text-transform: none; padding: 25px 30px; border-radius: 30px; font-size: 1.1rem; letter-spacing: 1px;">Contact Us <i class="fa-brands fa-whatsapp ms-2" style="color: lightgreen; font-size: 1.4rem;"></i></v-btn>
                </div>
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

.about-page {
    padding: 0vw 6vw;
    padding-bottom: 120px;
    padding-top: 120px;
    width: 100%; 
    display: flex;
    align-items: center;
    justify-content: center;
    color: #000000;
    background-color: #ffffff;
    /* background-image: linear-gradient(to right, #10131D,#151927,#1F2334,#4a3a4f); */
}
/* #112234 */

.card-about {
    /* background-color: #E0E7ED; */
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    /* align-items: center; */
    border-radius: 10px;
    width: 80vw;
}

.words-about {
    width: 40%;
    display: grid;
    justify-content: end;
    align-content: space-between;
}
.words-about h3 {
    font-size: 2.5rem;
}
.words-about p {
    font-size: 1.3rem;
    font-weight: 300;
    text-align: justify;
    margin-bottom: -40px;
}
.words-about h4 {
    font-size: 1.1rem;
}

.image-about {
    display: flex;
    justify-content: center;
    /* box-shadow: inset 0 0 12px 12px #F5F7FE, inset 0 0 3px 2px #F5F7FE;
    background: linear-gradient(to right, rgba(1, 184, 1, 0.275), rgba(184, 114, 1, 0.275), rgba(0, 255, 255, 0.292), rgba(0, 0, 255, 0.303), rgba(238, 130, 238, 0.303), rgba(128, 0, 128, 0.296));
    transform: translateY(25px) translateX(-25px); */
}

.image-about img{
    width: 40vw;
    max-height: 400px;
    border-radius: 20px;
    box-shadow: 0 0px 10px 1px #00000047;
}

/* .v-btn--is-elevated {
    box-shadow: none;
}
.rainbow {
    transform: translateY(30px) translateX(-8px);
    box-shadow: inset 0 0 12px 12px #F5F7FE, inset 0 0 3px 2px #F5F7FE;
    padding: 30px 8px; 
    width: fit-content;
    background: linear-gradient(to right, rgba(1, 184, 1, 0.179), rgba(0, 255, 255, 0.218), rgba(0, 0, 255, 0.207), rgba(238, 130, 238, 0.234), rgba(128, 0, 128, 0.211));
    border-radius: 45%;
} */

@media screen and (max-width: 1024px) {
    .image-about img{
        width: 80vw;
        max-height: 400px;
        margin-bottom: 60px;
    }
    .words-about {
        width: 100%;
        row-gap: 15px;
    }
    .words-about p {
        font-size: 1.1rem;
        font-weight: 300;
        text-align: justify;
    }
}

@media only screen and (max-width: 1024px) and (max-height: 1368px) and (min-height: 1024px) {

}


@media screen and (max-width: 576px) {
    .image-about img{
        width: 80vw;
        max-height: 300px;
        margin-bottom: 60px;
    }
    .words-about {
        width: 100%;
        row-gap: 15px;
    }
    .words-about p {
        font-size: 1rem;
        font-weight: 300;
        text-align: justify;
    }
}

</style>  