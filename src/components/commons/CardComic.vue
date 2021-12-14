<template>
    <div class="comic-card">
            <img :src="comic.thumb" :alt="comic.type">
            <h3>{{comic.series}}</h3>
    </div>
</template>

<script>
export default {
    name: 'CardComic',
    props:{
        comic: Object
    }
}
</script>

<style lang="scss" scoped>
    .comic-card{
        width: calc((100% / 6) - 30px);
        margin: 15px;
        img{
            width: 100%;
        }
    }
</style>