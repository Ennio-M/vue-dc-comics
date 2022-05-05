<template>
    <div class="container">
        <div class="card">
            <img src="../assets/imgs/buy-comics-digital-comics.png" alt="Digital Comics">
            <h4>Digital Comics</h4>
        </div>
        <div class="card">
            <img src="../assets/imgs/buy-comics-merchandise.png" alt="Merchandise">
            <h4>DC Merchandise</h4>
        </div>
        <div class="card">
            <img src="../assets/imgs/buy-comics-subscriptions.png" alt="Subscriptions">
            <h4>Subscription</h4>
        </div>
        <div class="card">
            <img src="../assets/imgs/buy-comics-shop-locator.png" alt="Shop Locator" class="small">
            <h4>Comic shop locator</h4>
        </div>
        <div class="card">
            <img src="../assets/imgs/buy-dc-power-visa.svg" alt="Power Visa">
            <h4>DC Power Visa</h4>
        </div>
    </div>
</template>

<script>
export default {
    name: 'MainSections'    
}
</script>

<style lang="scss" scoped>
    @import '../style/variables.scss';
    @import '../style/general.scss';

    .container{
        display: flex;
        gap: 20px;
        .card{
            display: flex;
            align-items: center;
            justify-content: space-evenly;
            height: 100%;
            width: calc(100% / 5);
            img{
                width: 40px;
            }
            h4{
                text-transform: uppercase;
                color: $white;
                font-weight: normal;
            }
        }
    }
    .small{
        width: 30px !important;
    }
</style>