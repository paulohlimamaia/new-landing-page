<template>
    <div class="bg-main-white">
        <navigation-menu></navigation-menu>
        <header class="container mx-auto">
            <div class="pt-16 mx-auto">    
                <div class="w-auto xs:m-0 md:m-1 md:pl-24 md:pr-24">
                    <h2 class="text-black font-black text-center" style="font-size: 65px;">
                        valtech_
                    </h2>
                    <hr class="border border-blue-light" style="width: 10%;">
                    <h1 class="text-black text-center font-light" style="font-size: 48px;">
                        The Podcast
                    </h1>
                    <br>
                    <div class="text-black font-black lg:text-4xl md:text-3xl sm:text-xl xs:text-lg mb-4 text-center">
                        <button class="button border font-black font-bold">LISTEN NOW</button>
                    </div>
                </div>
            </div>
        </header>
    
        <br>
    </div>
</template>

<script>
    import NavigationMenu from "./NavigationMenu";

    export default {
    components: {
        NavigationMenu
    },
    data() {
        return {};
    }
    };
</script>

<style scoped>
    .button {
        background-color: black; /* Green */
        border: none;
        color: white;
        padding: 20px 36px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 12px;
        letter-spacing: 1.5px;
    }
</style>
