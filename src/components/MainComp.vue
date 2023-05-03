<script>
export default {
    name: "MainComp",
    data() {
        return {

            linkBuy: [
                {
                    name: "DIGITAL COMICS",
                    url: "buy-comics-digital-comics.png",
                },
                {
                    name: "DC MERCHANDISE",
                    url: "buy-comics-merchandise.png",
                },
                {
                    name: "SUBSCRIPTION",
                    url: "buy-comics-subscriptions.png",
                },
                {
                    name: "COMIC SHOP LOCATOR",
                    url: "buy-comics-shop-locator.png",
                },
                {
                    name: "DC POWER VISA",
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
                    <!--? DIGITAL COMICS -->
                    <div class="col-2">
                        <a href="#">
                            <img class="me-3 section2_img" src="../../public/img/buy-comics-digital-comics.png"
                                alt="Digital_Comics">
                            <span class="text-nowrap fs text-light">DIGITAL COMICS</span>
                        </a>
                    </div>
                    <!--? DC MERCHANDISE -->
                    <div class="col-2">
                        <a href="#">
                            <img class="me-3 section2_img" src="../../public/img/buy-comics-merchandise.png"
                                alt="Digital_Comics">
                            <span class="text-nowrap fs text-light">DC MERCHANDISE</span>
                        </a>
                    </div>
                    <!--? SUBSCRIPTION -->
                    <div class="col-2">
                        <a href="#">
                            <img class="me-3 section2_img" src="../../public/img/buy-comics-subscriptions.png"
                                alt="Digital_Comics">
                            <span class="text-nowrap fs text-light">SUBSCRIPTION</span>
                        </a>
                    </div>
                    <!--? COMIC SHOP LOCATOR  -->
                    <div class="col-2">
                        <a href="#">
                            <img class="me-3" id="section2_img" src="../../public/img/buy-comics-shop-locator.png"
                                alt="Digital_Comics">
                            <span class="text-nowrap fs text-light">COMIC SHOP LOCATOR</span>
                        </a>
                    </div>
                    <!--? DC POWER VISA  -->
                    <div class="col-2">
                        <a href="#">
                            <img class="me-3 section2_img" src="../../public/img/buy-dc-power-visa.svg"
                                alt="Digital_Comics">
                            <span class="text-nowrap fs text-light">DC POWER VISA</span>
                        </a>
                    </div>
                </div>
            </div>
        </section>
    </main>
</template>

<!--! STYLE -->
<style scoped></style>