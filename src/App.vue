<template>
    <div id="test">
        <TitlePage></TitlePage>
        <HeroImage></HeroImage>
    </div>
</template>

<script>
import TitlePage from './components/TitlePage.vue'
import HeroImage from './components/HeroImage.vue'

export default {
    components:{
    TitlePage,
    HeroImage
}
}
</script>

<style>
    #test{
        position: relative;
    }
</style>