<script>
export default {
    name: "MainComp",
    data() {
        return {
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
            <div class="container_content">
                <h3> Content goes here </h3>
            </div>
        </section>
        <!--? SECTION 2 -->
        <section class="section_2 bg-primary">
            <div class="text-light p-5 w-75 container">
                <div class="row justify-content-between align-items-center">
                    <div class="col-2 d-flex align-items-center">
                        <img class="me-3  section2_img" src="../../public/img/buy-comics-digital-comics.png"
                            alt="Digital_Comics">
                        <span class="text-nowrap fs">DIGITAL COMICS</span>
                    </div>
                    <div class="col-2 d-flex align-items-center">
                        <img class="me-3  section2_img" src="../../public/img/buy-comics-merchandise.png"
                            alt="Digital_Comics">
                        <span class="text-nowrap fs">DC MERCHANDISE</span>
                    </div>
                    <div class="col-2 d-flex align-items-center">
                        <img class="me-3  section2_img" src="../../public/img/buy-comics-subscriptions.png"
                            alt="Digital_Comics">
                        <span class="text-nowrap fs">SUBSCRIPTION</span>
                    </div>
                    <div class="col-2 d-flex align-items-center">
                        <img class="me-3" id="section2_img" src="../../public/img/buy-comics-shop-locator.png"
                            alt="Digital_Comics">
                        <span class="text-nowrap fs">COMIC SHOP LOCATOR</span>
                    </div>
                    <div class="col-2 d-flex align-items-center">
                        <img class="me-3  section2_img" src="../../public/img/buy-dc-power-visa.svg" alt="Digital_Comics">
                        <span class="text-nowrap fs">DC POWER VISA</span>
                    </div>
                </div>
            </div>
        </section>
    </main>
</template>

<!--! STYLE -->
<style scoped></style>