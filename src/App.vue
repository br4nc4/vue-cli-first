<template>
    <div id="title">
        <TitlePage></TitlePage>
    </div>
</template>

<script>
import TitlePage from './components/TitlePage.vue'

export default {
    components:{
        TitlePage,
    }
}
</script>

<style>
    #title{
        text-align: center;
        margin-top: 5rem;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif, Geneva, Tahoma, sans-serif, 'Times New Roman', Times, serif;
        color: rgb(12, 12, 41);
    }
</style>