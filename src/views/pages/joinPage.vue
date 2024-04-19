<template>
    <div class="join-page">
        <div class="wrapper">
            <h1 style="font-size: 3.5rem; line-height: 1.2; text-align: center;">Take your holidays to the next<br>level starting today</h1>
            <v-btn style="background-color: #000000; color: #ffffff; width: fit-content; text-transform: none; padding: 25px 30px; border-radius: 30px; font-size: 1rem; letter-spacing: 1px;">Let's Get Started <i class="fa-brands fa-whatsapp ms-2" style="color: lightgreen; font-size: 1.3rem;"></i></v-btn>
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

.join-page {
    width: 100%;
    height: 700px;
    padding: 6vw 0;
    display: grid;
    align-items: start;
    justify-items: center;
    background-color: transparent;
    background-image: url(../../assets/images/join.png);
    background-size: cover;
    background-position: bottom left;
    background-repeat: no-repeat;
    /* background-attachment: fixed; */
}

.wrapper {
    display: grid;
    justify-items: center;
    gap: 30px;
}


@media screen and (max-width: 576px) {

}

</style>