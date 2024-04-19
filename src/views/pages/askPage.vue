<template>
    <div class="ask-page">
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
    padding: 70px 20px;
    display: grid;
    align-items: center;
    justify-items: center;
    background-color: #ffffff;
    color: #000000;
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

</style>