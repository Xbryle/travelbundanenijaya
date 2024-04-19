<template>
    <div class="map-page">
        <div class="maps" id="maps">
            <div class="mapouter">
                <div class="gmap_canvas">
                    <iframe class="gmap_iframe" width="100%" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://maps.google.com/maps?width=1007&amp;height=383&amp;hl=en&amp;q=Indonesia Samarinda jalan gelatik CV. Bunda Neni Jaya Travel&amp;t=p&amp;z=14&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"></iframe>
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

<style>

.map-page {
    width: 100%;
    padding: 2vw 0;
    display: grid;
    align-items: center;
    justify-items: center;
    background-image: url(../../assets/images/bg6.jpg);
    background-size: cover;
    background-position: top center;
    background-attachment: fixed;
}

.maps {
    padding: 20px;
    /* background-color: #F5F7FE; */
    width: 95%;
}
.mapouter {
    position: relative;
    text-align: right;
    width: 100%;
    height: 500px;
}
.gmap_canvas {
    overflow: hidden;
    background: none!important;
    width: 100%;
    height: 500px;
}
.gmap_iframe {
    height: 500px!important;
}


@media screen and (max-width: 576px) {

}

</style>