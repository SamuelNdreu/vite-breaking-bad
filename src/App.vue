<script>
import AppMain from './components/AppMain.vue'
// import AppLoader from './components/AppLoader.vue'
export default {
    name: "App",
    components: {
        AppMain,
        // AppLoader,
    }
}
</script>

<template>
    <main>
        <!-- <AppLoader /> -->
        <AppMain />
    </main>
    
</template>

<style scoped>
main{
    background-image: url(https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwallpaperbat.com%2Fimg%2F423333-blackarch-linux-ethical-hacking-os-gets-first-2020-release.jpg&f=1&nofb=1&ipt=7d1de32dfd003dcd527a69bc5c8011a179c9ccd42242803473b8ee1b671fbc94&ipo=images);
}

</style>
