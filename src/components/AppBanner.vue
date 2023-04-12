<script>
    export default {
        name: "AppBanner",
        data() {
            return {
                title: "Benvenuti a Stol'ano!"
            }
        }
    }
</script>

<template>
   <h2>{{ title }}</h2>
   <img class="banner-img" src="../assets/vue.svg" alt="">
</template>

<style>
</style>