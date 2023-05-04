<script>
export default {
    name: "FooterComp",
    data() {
        return {
            listaComics: [
                {
                    title: "DC COMICS",
                    linkComics: [
                        {
                            name: "Characters",
                            url: "/characters"
                        },
                        {
                            name: "Comics",
                            url: "/comics"
                        },
                        {
                            name: "Movies",
                            url: "/movies"
                        },
                        {
                            name: "TV",
                            url: "/tv"
                        },
                        {
                            name: "Games",
                            url: "/games"
                        },
                        {
                            name: "Videos",
                            url: "/videos"
                        },
                        {
                            name: "News",
                            url: "/news"
                        }
                    ],

                },
                {
                    title: "DC",
                    linkComics: [
                        {
                            name: "Terms Of Use",
                            url: "/Terms"
                        },
                        {
                            name: "Privacy policy (New)",
                            url: "/privacy"
                        },
                        {
                            name: "Ad Choices",
                            url: "/choices"
                        },
                        {
                            name: "Advertising",
                            url: "/tv"
                        },
                        {
                            name: "Jobs",
                            url: "/games"
                        },
                        {
                            name: "Subscriptions",
                            url: "/videos"
                        },
                        {
                            name: "Talent Workshops",
                            url: "/news"
                        },
                        {
                            name: "CPSC Certificates",
                            url: "/news"
                        },
                        {
                            name: "Ratings",
                            url: "/news"
                        },
                        {
                            name: "Shop Help",
                            url: "/news"
                        },
                        {
                            name: "Contact Us",
                            url: "/news"
                        }
                    ]

                },
                {
                    title: "SITES",
                    linkComics: [
                        {
                            name: "DC",
                            url: "/DC"
                        },
                        {
                            name: "MAD Magazine",
                            url: "/Magazine"
                        },
                        {
                            name: "DC Kids",
                            url: "/Kids"
                        },
                        {
                            name: "DC Universe",
                            url: "/Universe"
                        },
                        {
                            name: "DC Power Visa",
                            url: "/Power_Visa"
                        }
                    ]
                },
                {
                    title: "SHOP",
                    linkComics: [
                        {
                            name: "Shop DC",
                            url: "/Shop"
                        },
                        {
                            name: "Shop DC Collectibles",
                            url: "/Shop_Collectibles"
                        },
                    ]
                }
            ]
        }
    },
    methods: {
    },
};
</script>

<!--! TEMPLATE -->
<template>
    <footer>
        <!--? SECTION FOOTER 1 -->
        <section class="p-4 section_1">
            <div class="container-fluid d-flex position-relative">
                <div class="row">
                    <!--? LISTA DC COMICS -->
                    <div class="col-4">
                        <h2 class="text-light">{{ listaComics[0].title }}</h2>
                        <ul>
                            <li v-for="(comics, index) in listaComics[0].linkComics" :key="index">
                                <a :href="comics.url">{{ comics.name }}</a>
                            </li>
                        </ul>
                    </div>
                    <!--? LISTA DC -->
                    <div class="col-4">
                        <h2 class="text-light">{{ listaComics[1].title }}</h2>
                        <ul>
                            <li v-for="(dc, index) in listaComics[1].linkComics" :key="index">
                                <a :href="dc.url">{{ dc.name }}</a>
                            </li>
                        </ul>
                    </div>
                    <!--? LISTA SITES -->
                    <div class="col-4">
                        <h2 class="text-light">{{ listaComics[2].title }}</h2>
                        <ul>
                            <li v-for="(sites, index) in listaComics[2].linkComics" :key="index">
                                <a :href="sites.url">{{ sites.name }}</a>
                            </li>
                        </ul>
                    </div>
                    <!--? LISTA SHOP -->
                    <div class="col-4">
                        <h2 class="text-light">{{ listaComics[3].title }}</h2>
                        <ul>
                            <li v-for="(shop, index) in listaComics[3].linkComics" :key="index">
                                <a :href="shop.url">{{ shop.name }}</a>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="img_footer">
                    <img src="../../public/img/dc-logo-bg.png" alt="">
                </div>
            </div>
        </section>
        <!--? SECTION FOOTER 2 -->
        <section class="section_2">
            <div class="container-fluid d-flex justify-content-between align-items-center">
                <div>
                    <button type="button" class="p-2">SIGN-UP NOW!</button>
                </div>
                <div class="d-flex gap-4 align-items-center container_social">
                    <h3 class="text-primary fs-5 mb-0">FOLLOW US</h3>
                    <a href="#">
                        <img src="../../public/img/footer-facebook.png" alt="Facebook_logo">
                    </a>
                    <a href="#">
                        <img src="../../public/img/footer-twitter.png" alt="Twitter_logo">
                    </a>
                    <a href="#">
                        <img src="../../public/img/footer-youtube.png" alt="Youtube_logo">
                    </a>
                    <a href="#">
                        <img src="../../public/img/footer-pinterest.png" alt="Pinterest_logo">
                    </a>
                    <a href="#">
                        <img src="../../public/img/footer-periscope.png" alt="Periscope_logo">
                    </a>
                </div>
            </div>
        </section>
    </footer>
</template>

<!--! STYLE -->
<style scoped></style>