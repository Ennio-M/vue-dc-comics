<template>
    <main>
        <div class="content">
            <div class="container">
                <h2>--&gt; Content goes here &lt;--</h2>
            </div>
        </div>
        <div class="sections">
            <div class="container">
            
            </div>
        </div>
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
        height: 150px;
        background-color: $dc-blue;
    }
</style>