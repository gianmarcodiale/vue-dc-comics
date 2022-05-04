<template>
    <section>
        <div class="container">
            <div class="row">
                <div class="col">
                    <button>SIGN UP NOW!</button>
                </div>
                <div class="social-links col d-flex align-items-center justify-content-end">
                    <h4>FOLLOW US</h4>
                    <img src="@/assets/img/footer-facebook.png" alt="" class="img-fluid">
                    <img src="@/assets/img/footer-twitter.png" alt="" class="img-fluid">
                    <img src="@/assets/img/footer-youtube.png" alt="" class="img-fluid">
                    <img src="@/assets/img/footer-pinterest.png" alt="" class="img-fluid">
                    <img src="@/assets/img/footer-periscope.png" alt="" class="img-fluid">
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "SiteSocials"
}
</script>

<style lang="scss" scoped>
@import "@/assets/sass/_variables.scss";

section {
    background-color: $footerColor;
    padding: 2rem;

    button {
        border: 1px solid $brandColor;
        background-color: transparent;
        color: white;
        padding: 0.75rem;
    }

    h4 {
        color: $brandColor;
        margin-bottom: 0;
        font-size: 1.25rem;
    }

    img {
        width: 30px;
    }

    .social-links {
        column-gap: 0.5rem;
    }
}
</style>