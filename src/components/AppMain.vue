<template>
    <main>
        <section class="content">
            <JumboTron/>
            <div class="container">
                
            </div>
        </section>
        <section class="sections">
            <MainSections/>
        </section>
    </main>
</template>

<script>
import MainSections from './MainSections.vue'
import JumboTron from './JumboTron.vue'

export default {
    name: 'AppMain',
    components: {
        MainSections,
        JumboTron
    }   
}
</script>

<style lang="scss" scoped>
    @import '../style/variables.scss';
    @import '../style/general.scss';

    .content{
        height: 400px;
    }
    .sections{
        height: 130px;
        background-color: $dc-blue;
    }
</style>