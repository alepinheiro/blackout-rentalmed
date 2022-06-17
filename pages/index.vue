<script setup>
    import { Icon } from '@iconify/vue'

    useHead({
        title: 'Aparelhos de Estética e Fisioterapia em até 60x - Rentalmed',
        //description: 'Loja especializada em aparelhos para estética e fisioterapia. Só na RentalMed você encontra as melhores marcas em até 60X.',
        viewport: 'width=device-width, initial-scale=1, maximum-scale=1',
        charset: 'utf-8',
        meta: [
            { name: 'description', content: 'Loja especializada em aparelhos para estética e fisioterapia. Só na RentalMed você encontra as melhores marcas em até 60X.' },
            { property: 'og:locale', content: 'pt_BR' },
            { property: 'og:type', content: 'website' },
            { property: 'og:title', content: 'Aparelhos de Estética e Fisioterapia em até 60x - Rentalmed' },
            { property: 'og:description', content: 'Loja especializada em aparelhos para estética e fisioterapia. Só na RentalMed você encontra as melhores marcas em até 60X.' },
        ],
        bodyAttrs: {
            class: 'test'
        }
    })

</script>

<script>
    export default {
        methods: {
            sendToWhatsApp: function (){
                window.location.href =
                    'https://api.whatsapp.com/send/?phone=5548985050350&text=Estou%20no%20site%20da%20rentalmed%20e%20gostaria%20de%20falar%20com%20um%20atendente.'
            }
        }
    }

</script>

<template>

    <div class="bg-black min-h-screen text-white font-outfit h-full flex flex-col justify-center items-center relative">



        <div class="flex flex-col max-w-xl m-auto items-center justify-center gap-10 z-10 mx-5 text-center my-48">

            <h1 class="text-3xl">
                Isso é um até logo.
            </h1>

            <p>
                A Rentalmed que você coonhece nunca mais será a mesma.
            </p>

            <p class="text-pink-500">
                <b>
                    Na segunda-feira, dia 20/06, tudo vai mudar!
                </b>
            </p>

            <div class="flex flex-col gap-4">
                <p>
                    Estaremos atendendo normalmente pelo whatsapp!
                </p>

                <button
                    v-on:click="sendToWhatsApp"
                    class="bg-purple-600 hover:bg-purple-800 px-4 py-2 rounded uppercase w-fit mx-auto"
                >
                    Fale com nossos atendentes
                </button>
            </div>

            <p>
                <b>
                    Entre em contato e descubra as promoções que estão rolando!
                </b>
            </p>

            <div class="flex flex-col items-center gap-2">
                <h1 class="text-2xl my-4">
                    <b> blackout </b> rentalmed
                </h1>

                <div class="flex flex-col md:flex-row gap-4">

                    <a href="https://instagram.com/rentalmed" class="flex flex-row">
                        <div class="w-6 h-6 mr-2">
                            <Icon icon="akar-icons:instagram-fill" height="100%"/>
                        </div>
                        <div>
                            rentalmed
                        </div>
                    </a>

                    <a href="https://youtube.com.br/rentalmed" class="flex flex-row">
                        <div class="w-6 h-6 mr-2">
                            <Icon icon="ant-design:youtube-outlined" height="100%"/>
                        </div>
                        <div>
                            rentalmed
                        </div>
                    </a>

                    <a href="https://facebook.com/rentalmed" class="flex flex-row">
                        <div class="w-6 h-6 mr-2">
                            <Icon icon="akar-icons:facebook-fill" height="100%"/>
                        </div>
                        <div>
                            rentalmed
                        </div>
                    </a>
                </div>
            </div>

        </div>


        <div class="absolute h-fit w-fit top-0 left-0 ">
            <img src="@/assets/images/04.png" class="h-48 md:h-96">
        </div>

        <div class="absolute h-fit w-fit bottom-0 right-0 ">
            <img src="@/assets/images/01.png" class="h-48 md:h-96">
        </div>


    </div>

</template>

<style>


</style>