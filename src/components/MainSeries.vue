<script>
export default {
    name: "MainSeries",

    props: ['seriesComics']
};
</script>

<!--! TEMPLATE -->
<template>
    <div class="col-2">
        <a href="#">
            <img :src="seriesComics.thumb" :alt="seriesComics.series" class="pb-3">
        </a>
        <a href="#">
            <h4 class="text-light mb-5">{{ seriesComics.series }}</h4>
        </a>
    </div>
</template>

<!--! STYLE -->
<style lang="scss" >
#sectionCSeries {

    position: relative;
    background-color: #1c1c1c;

    #containerSeries {

        .col-2 {

            &:hover {
                filter: brightness(0.5);
            }

            a {

                text-decoration: none;


                img {
                    width: 100%;
                    height: 300px;
                }

                h4 {
                    font-size: 15px;
                    text-transform: uppercase;
                }
            }
        }

    }
}
</style>