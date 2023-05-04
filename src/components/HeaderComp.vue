<script>
export default {
    name: "HeaderComp",
    data() {
        return {
            navBar: [
                {
                    name: "CHARACTERS",
                    url: "/characters",
                    current: false
                },
                {
                    name: "COMICS",
                    url: "/comics",
                    current: true
                },
                {
                    name: "MOVIES",
                    url: "/movies",
                    current: false
                },
                {
                    name: "TV",
                    url: "/tv",
                    current: false
                },
                {
                    name: "GAMES",
                    url: "/games",
                    current: false
                },
                {
                    name: "COLLECTIBLES",
                    url: "/collectibles",
                    current: false
                },
                {
                    name: "VIDEOS",
                    url: "/videos",
                    current: false
                },
                {
                    name: "FANS",
                    url: "/fans",
                    current: false
                },
                {
                    name: "NEWS",
                    url: "/news",
                    current: false
                },
                {
                    name: "SHOP",
                    url: "/shop",
                    current: false
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
                    <li v-for="(navBarName, index) in navBar" :key="index" :class="navBarName.current ? 'active' : ''">
                        <a :href="navBarName.url" :class="navBarName.current ? 'active' : ''"><strong>{{ navBarName.name
                        }}</strong></a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>
</template>

<!--! STYLE -->
<style scoped></style>