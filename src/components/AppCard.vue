<template>
    <div class="card">
        <div class="thumb">
            <img :src="image" :alt="series">
        </div>
        <div class="description">
            <h5>{{series}}</h5>
        </div>
    </div>
</template>

<script>
export default {
    name: 'AppCard',
    props: {
        image: String,
        series: String
    }
}
</script>

<style lang="scss" scoped>
    @import '../style/variables.scss';

    .card{
        width: calc((100% - 150px) / 6);

        .thumb{
            height: 160px;
            overflow: hidden;
            img{
                width: 100%;
                cursor: pointer;
            }
        }
        .description{
            padding-top: 15px;
        }
        h5{
            color: $white;
            font-weight: 400;
            text-transform: uppercase;
        }
    }
</style>