<template>
    <section>
        <div class="container">
            <div class="row">
                <div class="col d-flex align-items-center">
                    <img src="@/assets/img/buy-comics-digital-comics.png" alt="" class="img-fluid">
                    <a href="#">Digital Comics</a>
                </div>
                <div class="col d-flex align-items-center">
                    <img src="@/assets/img/buy-comics-merchandise.png" alt="" class="img-fluid">
                    <a href="#">DC Merchandise</a>
                </div>
                <div class="col d-flex align-items-center">
                    <img src="@/assets/img/buy-comics-subscriptions.png" alt="" class="img-fluid">
                    <a href="#">Subscription</a>
                </div>
                <div class="col d-flex align-items-center">
                    <img src="@/assets/img/buy-comics-shop-locator.png" alt="" class="img-fluid">
                    <a href="#">Comic Shop Locator</a>
                </div>
                <div class="col d-flex align-items-center">
                    <img src="@/assets/img/buy-dc-power-visa.svg" alt="" class="img-fluid">
                    <a href="#">DC Power Visa</a>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'SiteShopSection',
}
</script>

<style lang="scss" scoped>
@import "@/assets/sass/_variables.scss";

section {
    background-color: $brandColor;
    padding: 4rem;

    a {
        text-decoration: none;
        color: white;
        text-transform: uppercase;
        padding: 1rem;
        font-size: 0.9rem;
    }

    img {
        width: 40px;
    }
}
</style>