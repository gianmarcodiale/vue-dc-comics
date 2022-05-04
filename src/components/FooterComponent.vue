<template>
    <footer>
        <div class="container">
            <div class="row">
                <div class="col footer-links">
                    <div class="row">
                        <div class="col" v-for="item in footerMenu" :key="item.title">
                            <h4>{{item.title}}</h4>
                            <ul>
                                <li v-for="(link, index) in item.links" :key="index">
                                    <a :href="link.href">{{link.text}}</a>
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
    name: "FooterComponent",
    data() {
        return {
            footerMenu: [
                {
                    title: 'DC Comics',
                    links: [
                        {
                            href: '#',
                            text: 'Characters'
                        },
                        {
                            href: '#',
                            text: 'Comics'
                        },
                        {
                            href: '#',
                            text: 'Movies'
                        },
                        {
                            href: '#',
                            text: 'TV'
                        },
                        {
                            href: '#',
                            text: 'Games'
                        },
                        {
                            href: '#',
                            text: 'Videos'
                        },
                        {
                            href: '#',
                            text: 'News'
                        },
                    ]
                },
                {
                    title: 'Shop',
                    links: [
                        {
                            href: '#',
                            text: 'Shop DC'
                        },
                        {
                            href: '#',
                            text: 'Shop DC Collectibles'
                        }
                    ]
                },
                {
                    title: 'DC',
                    links: [
                        {
                            href: '#',
                            text: 'Terms Of Use'
                        },
                        {
                            href: '#',
                            text: 'Privacy policy'
                        },
                        {
                            href: '#',
                            text: 'Ad Choices'
                        },
                        {
                            href: '#',
                            text: 'Advertising'
                        },
                        {
                            href: '#',
                            text: 'Jobs'
                        },
                        {
                            href: '#',
                            text: 'Subscriptions'
                        },
                        {
                            href: '#',
                            text: 'Talent Workshop'
                        },
                        {
                            href: '#',
                            text: 'CPSC Certificates'
                        },
                        {
                            href: '#',
                            text: 'Ratings'
                        },
                        {
                            href: '#',
                            text: 'Shop Help'
                        },
                        {
                            href: '#',
                            text: 'Contact Us'
                        }
                    ]
                },
                {
                    title: 'Sites',
                    links: [
                        {
                            href: '#',
                            text: 'DC'
                        },
                        {
                            href: '#',
                            text: 'MAD Magazine'
                        },
                        {
                            href: '#',
                            text: 'DC Kids'
                        },
                        {
                            href: '#',
                            text: 'DC Universe'
                        },
                        {
                            href: '#',
                            text: 'DC Power Visa'
                        }
                    ]
                }
            ]
        
        }
    }
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
        text-transform: uppercase;
        font-size: 1.25rem;
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