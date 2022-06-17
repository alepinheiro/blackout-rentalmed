<script>

    export default {
        created(){
            this.$router.push('/?redirect')
        },
    }

</script>

<template>

    <div class="bg-black min-h-screen text-white font-outfit h-full flex flex-col justify-center items-center relative">


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