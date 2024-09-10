<template>
    <div class="ask-page">

        <div class="custom-shape-divider-top-1725966836">
            <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
                <path d="M321.39,56.44c58-10.79,114.16-30.13,172-41.86,82.39-16.72,168.19-17.73,250.45-.39C823.78,31,906.67,72,985.66,92.83c70.05,18.48,146.53,26.09,214.34,3V0H0V27.35A600.21,600.21,0,0,0,321.39,56.44Z" class="shape-fill"></path>
            </svg>
        </div>

        <div class="custom-shape-divider-bottom-1725967119">
            <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
                <path d="M321.39,56.44c58-10.79,114.16-30.13,172-41.86,82.39-16.72,168.19-17.73,250.45-.39C823.78,31,906.67,72,985.66,92.83c70.05,18.48,146.53,26.09,214.34,3V0H0V27.35A600.21,600.21,0,0,0,321.39,56.44Z" class="shape-fill"></path>
            </svg>
        </div>

        <h1 style="text-align: center; line-height: 1.1; margin-bottom: 20px;">Paling sering ditanya</h1>
        <p class="mb-10" style="font-size: .9rem; text-align: center;">Semua yang anda ingin tahu tentang cara kerja kami</p>
        <div class="expand-wrapper">
            <v-expansion-panels class="expandsions" style="border: 1px solid #dad9d9; width: inherit;" focusable flat>
                <v-expansion-panel>
                    <v-expansion-panel-header style="line-height: 1.3;">
                        Pesan tiket pesawat dan kapal secara offline?
                        <!-- <template v-slot:actions>
                            <v-icon color="black">
                            fa-solid fa-circle-plus
                            </v-icon>
                        </template> -->
                    </v-expansion-panel-header>
                    <v-expansion-panel-content class="pt-4">
                        Jika anda merasa ragu untuk memesan tiket pesawat dan kapal secara online, anda bisa datang langsung ke kantor kami yang ber alamat <span style="font-weight: 500;">Jln. Gelatik, Samping Gang Surya, Samarinda, Kalimantan Timur</span>, atau anda bisa lihat detailnya di peta.
                    </v-expansion-panel-content>
                </v-expansion-panel>
            </v-expansion-panels>

            <v-expansion-panels class="expandsions" style="border: 1px solid #dad9d9; width: inherit;" focusable flat>
                <v-expansion-panel>
                    <v-expansion-panel-header style="line-height: 1.3;">
                        Apakah ada biaya tambahan untuk duduk di kursi depan?
                        <!-- <template v-slot:actions>
                            <v-icon color="black">
                            fa-solid fa-circle-plus
                            </v-icon>
                        </template> -->
                    </v-expansion-panel-header>
                    <v-expansion-panel-content class="pt-4">
                        Anda akan dikenakan tarif tambahan untuk duduk di kursi depan sebesar <span style="font-weight: 500;">Rp. 50.000,00</span>,  dikarenakan kursi depan memiliki beberapa keuntungan selama perjalanan dan menghindari pertikaian perebutan tempat duduk.
                    </v-expansion-panel-content>
                </v-expansion-panel>
            </v-expansion-panels>

            <v-expansion-panels class="expandsions" style="border: 1px solid #dad9d9; width: inherit;" focusable flat>
                <v-expansion-panel>
                    <v-expansion-panel-header style="line-height: 1.3;">
                        Apakah bisa bepergian tanpa harus datang ke kantor?
                        <!-- <template v-slot:actions>
                            <v-icon color="black">
                            fa-solid fa-circle-plus
                            </v-icon>
                        </template> -->
                    </v-expansion-panel-header>
                    <v-expansion-panel-content class="pt-4">
                        Duduk Manis di Mana Saja, Kami Jemput Anda! Pesan kursi tanpa harus datang ke kantor kami. Cukup beritahu alamat Anda, dan kami akan jemput Anda tepat waktu.
                    </v-expansion-panel-content>
                </v-expansion-panel>
            </v-expansion-panels>

            <v-expansion-panels class="expandsions" style="border: 1px solid #dad9d9; width: inherit;" focusable flat>
                <v-expansion-panel>
                    <v-expansion-panel-header style="line-height: 1.3;">
                        Apakah bisa bepergian tetapi dari luar kota Samarinda?
                        <!-- <template v-slot:actions>
                            <v-icon color="black">
                            fa-solid fa-circle-plus
                            </v-icon>
                        </template> -->
                    </v-expansion-panel-header>
                    <v-expansion-panel-content class="pt-4">
                        Anda bisa memesan kursi walaupun dari luar kota Samarinda, cukup hubungi kami dan akan kami carikan supir yang sedang bersiaga di kota anda.
                    </v-expansion-panel-content>
                </v-expansion-panel>
            </v-expansion-panels>

            <v-expansion-panels class="expandsions" style="border: 1px solid #dad9d9; width: inherit;" focusable flat>
                <v-expansion-panel>
                    <v-expansion-panel-header style="line-height: 1.3;">
                        Buka hingga jam berapa?
                        <!-- <template v-slot:actions>
                            <v-icon color="black">
                            fa-solid fa-circle-plus
                            </v-icon>
                        </template> -->
                    </v-expansion-panel-header>
                    <v-expansion-panel-content class="pt-4">
                        Kami siap melayani anda 24 jam.
                    </v-expansion-panel-content>
                </v-expansion-panel>
            </v-expansion-panels>
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

.ask-page {
    width: 100%;
    padding: 180px 20px;
    display: grid;
    align-items: center;
    justify-items: center;
    background-image: linear-gradient(to bottom right, #ff49b0, #ec8d35);
    background-color: #0000002f;
    background-blend-mode: overlay;
    color: #FFFFFF;
    position: relative;
}

.expand-wrapper {
    width: 60vw;
    /* background-color: aquamarine; */
    display: grid;
    justify-content: center;
    align-items: start;
    row-gap: 10px;
}
.expandsions {
    /* background-color: blue; */
    background-color: #dad9d9;
    box-shadow: transparent;
}

@media screen and (max-width: 576px) {
    .expand-wrapper {
        width: 90vw;
    }
}





.custom-shape-divider-top-1725966836 {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
}

.custom-shape-divider-top-1725966836 svg {
    position: relative;
    display: block;
    width: calc(180% + 1.3px);
    height: 150px;
}

.custom-shape-divider-top-1725966836 .shape-fill {
    fill: #FFFFFF;
}



.custom-shape-divider-bottom-1725967119 {
    position: absolute;
    bottom: -1px;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
    transform: rotate(180deg);
}

.custom-shape-divider-bottom-1725967119 svg {
    position: relative;
    display: block;
    width: calc(180% + 1.3px);
    height: 150px;
}

.custom-shape-divider-bottom-1725967119 .shape-fill {
    fill: #FFFFFF;
}

</style>