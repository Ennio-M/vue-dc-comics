<template>
    <main>
        <JumboTron/>
        <section class="cards-container">
            <CardsContainer/>
        </section>
        <section class="sections">
            <MainSections/>
        </section>
    </main>
</template>

<script>
import MainSections from './MainSections.vue'
import JumboTron from './JumboTron.vue'
import CardsContainer from './CardsContainer.vue'

export default {
    name: 'AppMain',
    components: {
        MainSections,
        JumboTron,
        CardsContainer
    }   
}
</script>

<style lang="scss" scoped>
    @import '../style/variables.scss';
    @import '../style/general.scss';

    .cards-container{
        background-color: $darker;
    }
    .sections{
        height: 130px;
        background-color: $dc-blue;
    }
</style>