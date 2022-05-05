<template>
    <main>
        <section class="content">
            <div class="container">
                <h2>--&gt; Content goes here &lt;--</h2>
            </div>
        </section>
        <section class="sections">
            <div class="container">
            
            </div>
        </section>
    </main>
</template>

<script>
export default {
    name: 'AppMain'    
}
</script>

<style lang="scss" scoped>
    @import '../style/variables.scss';
    @import '../style/general.scss';

    .content{
        height: 120px;
        background-color: $black;
        color: $white;
        line-height: 120px;
    }
    .sections{
        height: 140px;
        background-color: $dc-blue;
    }
</style>