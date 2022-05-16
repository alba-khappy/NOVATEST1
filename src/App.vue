<template lang="pug">
    div
        header-component
        main
            section-logline
            section-actors
            section-footage
            section-shops
        footer-component

</template>

<script>

    import HeaderComponent from "./components/HeaderComponent";
    import FooterComponent from "./components/FooterComponent";
    import SectionLogline from "./components/SectionLogline";
    import SectionActors from "./components/SectionActors";
    import SectionFootage from "./components/SectionFootage";
    import SectionShops from "./components/SectionShops";

    export default {
        data (){
            return {
            }
        },
        name: 'App',
        components: {
            SectionShops,
            SectionFootage,
            SectionActors,
            SectionLogline,
            FooterComponent,
            HeaderComponent,
        },
    }

</script>

<style lang="scss">
    @import "./assets/scss/general.scss";

</style>
