<template>
    <footer>
        <div class="container">
            <div class="row">
                <div class="col footer-links">
                    <div class="row">
                        <div class="col">
                            <h4>DC COMICS</h4>
                            <ul>
                                <li>
                                    <a href="#">Characters</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Movies</a>
                                </li>
                                <li>
                                    <a href="#">TV</a>
                                </li>
                                <li>
                                    <a href="#">Games</a>
                                </li>
                                <li>
                                    <a href="#">Videos</a>
                                </li>
                                <li>
                                    <a href="#">News</a>
                                </li>
                            </ul>
                            <h4>SHOP</h4>
                            <ul>
                                <li>
                                    <a href="#">Shop DC</a>
                                </li>
                                <li>
                                    <a href="#">Shop DC Collectibles</a>
                                </li>
                            </ul>
                        </div>
                        <div class="col">
                            <h4>DC</h4>
                            <ul>
                                <li>
                                    <a href="#">Terms Of Use</a>
                                </li>
                                <li>
                                    <a href="#">Privacy policy</a>
                                </li>
                                <li>
                                    <a href="#">Ad Choices</a>
                                </li>
                                <li>
                                    <a href="#">Advertising</a>
                                </li>
                                <li>
                                    <a href="#">Jobs</a>
                                </li>
                                <li>
                                    <a href="#">Subscriptions</a>
                                </li>
                                <li>
                                    <a href="#">Talent Workshops</a>
                                </li>
                                <li>
                                    <a href="#">CPSC Certificates</a>
                                </li>
                                <li>
                                    <a href="#">Ratings</a>
                                </li>
                                <li>
                                    <a href="#">Shop Help</a>
                                </li>
                                <li>
                                    <a href="#">Contact Us</a>
                                </li>
                            </ul>
                        </div>
                        <div class="col">
                            <h4>SITES</h4>
                            <ul>
                                <li>
                                    <a href="#">DC</a>
                                </li>
                                <li>
                                    <a href="#">MAD Magazine</a>
                                </li>
                                <li>
                                    <a href="#">DC Kids</a>
                                </li>
                                <li>
                                    <a href="#">DC Universe</a>
                                </li>
                                <li>
                                    <a href="#">DC Power Visa</a>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col dc-logo">
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: "FooterComponent"
}
</script>

<style lang="scss" scoped>
@import "@/assets/sass/_variables.scss";

footer {
    background-image: url("@/assets/img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-size: cover;

    .dc-logo {
        background-image: url("@/assets/img/dc-logo-bg.png");
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;
    }

    .footer-links {
        padding: 4rem;
    }

    h4 {
        color: white;
    }

    ul {
        padding-inline-start: 0;
    }

    a {
        text-decoration: none;
        color: $footerTextColor;
    }
}
</style>