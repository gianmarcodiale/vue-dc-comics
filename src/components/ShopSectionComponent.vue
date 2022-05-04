<template>
    <section>
        <div class="container">
            <div class="row">
                <div class="col d-flex align-items-center" v-for="item in bannerList" :key="item.id">
                    <img :src="item.src" alt="" class="img-fluid">
                    <a href="#">{{item.text}}</a>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'SiteShopSection',
    data() {
        return {
            bannerList: [
                {
                    id: 1,
                    src: require('@/assets/img/buy-comics-digital-comics.png'),
                    text: 'Digital Comics'
                },
                {
                    id: 2,
                    src: require('@/assets/img/buy-comics-merchandise.png'),
                    text: 'DC Merchandise'
                },
                {
                    id: 3,
                    src: require('@/assets/img/buy-comics-subscriptions.png'),
                    text: 'Subscription'
                },
                {
                    id: 4,
                    src: require('@/assets/img/buy-comics-shop-locator.png'),
                    text: 'Comic Shop Locator'
                },
                {
                    id: 5,
                    src: require('@/assets/img/buy-dc-power-visa.svg'),
                    text: 'DC Power Visa'
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import "@/assets/sass/_variables.scss";

section {
    background-color: $brandColor;
    padding: 4rem 0;

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