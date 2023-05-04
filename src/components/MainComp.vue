<script>
export default {
    name: "MainComp",
    data() {
        return {
            path: "../../public/img/",

            linkBuy: [
                {
                    name: "DIGITAL COMICS",
                    alt: "Digital_Comics",
                    url: "buy-comics-digital-comics.png",
                },
                {
                    name: "DC MERCHANDISE",
                    alt: "Dc_Merchandise",
                    url: "buy-comics-merchandise.png",
                },
                {
                    name: "SUBSCRIPTION",
                    alt: "Subscription",
                    url: "buy-comics-subscriptions.png",
                },
                {
                    name: "COMIC SHOP LOCATOR",
                    alt: "Comic_Shop_Locator",
                    url: "buy-comics-shop-locator.png",
                },
                {
                    name: "DC POWER VISA",
                    alt: "Dc_Power_Visa",
                    url: "buy-dc-power-visa.svg",
                },
            ]
        }
    },
    methods: {
    },
};
</script>

<!--! TEMPLATE -->
<template>
    <main>
        <!--? SECTION 1 -->
        <section class="bg-dark">
            <div class="container_content d-flex align-items-center container">
                <h3 class="text-light"> Content goes here </h3>
            </div>
        </section>
        <!--? SECTION 2 -->
        <section class="section_2 bg-primary">
            <div class="p-5 w-75 container">
                <div class="row justify-content-between align-items-center">
                    <div v-for="(shop, index) in linkBuy" :key="index" class="col-2">
                        <a :href="shop.url">
                            <img class="me-3 section2_img" :src="path + shop.url" :alt="shop.alt"
                                :id="(index == 3) ? 'section2_img' : ''">
                            <span class="text-nowrap fs text-light">{{ shop.name }}</span>
                        </a>
                    </div>
                </div>
            </div>
        </section>
    </main>
</template>

<!--! STYLE -->
<style scoped></style>