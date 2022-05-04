<template>
    <header id="SiteHeader">
        <div class="container">
            <div class="row align-items-center">
                <div class="col">
                    <div class="logo">
                        <img src="@/assets/img/dc-logo.png" alt="" class="img-fluid">
                    </div>
                </div>
                <div class="col">
                    <nav>
                        <a href="#" v-for="(item, index) in navLinks" :key="index">{{item.link}}</a>
                    </nav>
                </div>
            </div>
        </div>
    </header>
</template>

<script>

export default {
    name: 'HeaderComponent',
    data() {
        return {
            navLinks: [
                {
                    link: "Characters"
                },
                {
                    link: "Comics"
                },
                {
                    link: "Movies"
                },
                {
                    link: "TV"
                },
                {
                    link: "Games"
                },
                {
                    link: "Collectibles"
                },
                {
                    link: "Videos"
                },
                {
                    link: "Fans"
                },
                {
                    link: "News"
                },
                {
                    link: "Shop"
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
header {
    padding: 1rem;
    
    a {
        text-decoration: none;
        text-transform: uppercase;
        padding: 0.5rem;
        font-size: 0.9rem;
        font-weight: 600;
        color: black;
    }
}
</style>