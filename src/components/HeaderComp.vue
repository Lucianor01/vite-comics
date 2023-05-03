<script>
export default {
    name: "HeaderComp",
    data() {
        return {
            navBar: [
                {
                    name: "CHARACTERS",
                    url: "/characters"
                },
                {
                    name: "COMICS",
                    url: "/comics"
                },
                {
                    name: "MOVIES",
                    url: "/movies"
                },
                {
                    name: "TV",
                    url: "/tv"
                },
                {
                    name: "GAMES",
                    url: "/games"
                },
                {
                    name: "COLLECTIBLES",
                    url: "/collectibles"
                },
                {
                    name: "VIDEOS",
                    url: "/videos"
                },
                {
                    name: "FANS",
                    url: "/fans"
                },
                {
                    name: "NEWS",
                    url: "/news"
                },
                {
                    name: "SHOP",
                    url: "/characters"
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
    <header>
        <nav>
            <!--? IMMAGINE NAVBAR -->
            <div>
                <img src="../../public/img/dc-logo.png" alt="Logo">
            </div>
            <!--? LISTA NAVBAR -->
            <div>
                <ul>
                    <li v-for="(navBarName, index) in navBar" :key="index">
                        <a :href="navBarName.url"><strong>{{ navBarName.name }}</strong></a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>
</template>

<!--! STYLE -->
<style scoped></style>