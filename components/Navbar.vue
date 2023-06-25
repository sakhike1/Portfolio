<template>
    <div id="app">
        <Title>sakhile Simelane </Title>
        <div id=" nav" class="bg-gradient-to-b from-[#101212] relative to-[#08201D] py-2">
            <nav class="container px-6 py-6 mx-auto md:flex md:justify-between md:items-center">
                <div class="flex items-center justify-between">
                    <nuxt-link to="/"
                        class=" text-transparent bg-clip-text text-white md:text-2xl hover:text-blue-200">Sakhile
                        Simelane
                    </nuxt-link>
                    <!-- Mobile menu button -->
                    <div @click="toggleNav" class="flex-end md:hidden">
                        <button type="button"
                            class="text-white hover:text-gray-1000 focus:outline-none focus:text-gray-100">
                            <svg viewBox="0 0 24 24" class="w-6 h-6 fill-current">
                                <path fill-rule="evenodd"
                                    d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z">
                                </path>
                            </svg>
                        </button>
                    </div>
                </div>

                <!-- Mobile Menu open: "block", Menu closed: "hidden" -->
                <ul :class="showMenu ? 'flex' : 'hidden'"
                    class="flex-col mt-4 m-2 space-y-4 md:flex md:space-y-0 md:flex-row md:items-center md:space-x-10 md:mt-0">
                    <li>
                        <nuxt-link class="text-gray-100 text-tahiti text-sm hover:text-blue-300" to="/">
                            Home</nuxt-link>
                    </li>
                    <li>
                        <nuxt-link class="text-gray-100 text-tahiti text-sm hover:text-blue-300" to="designs">
                            my design</nuxt-link>
                    </li>
                    <li>
                        <nuxt-link class="joinBtn text-gray-100 text-tahiti text-sm hover:text-blue-300 " to="about">About
                            me
                        </nuxt-link>
                    </li>
                    <li>
                        <nuxt-link class="joinBtn text-gray-100 text-tahiti text-sm hover:text-blue-300 "
                            to="contact">Contact

                        </nuxt-link>
                    </li>


                    <li class="pt-2 ">
                        <a href="https://dribbble.com/shots/16444047-Thumela-imali-app-for-all-your-payment-needs"
                            class="relative px-6 py-3 font-bold text-white rounded-lg group">
                            <span
                                class="absolute inset-0 w-full h-full transition duration-300 transform -translate-x-1 -translate-y-1 bg-purple-800 ease opacity-80 group-hover:translate-x-0 group-hover:translate-y-0"></span>
                            <span
                                class="absolute inset-0 w-full h-full transition duration-300 transform translate-x-1 translate-y-1 bg-pink-800 ease opacity-80 group-hover:translate-x-0 group-hover:translate-y-0 mix-blend-screen"></span>
                            <span class="relative">View Work</span>
                        </a>
                    </li>
                </ul>
            </nav>
        </div>
    </div>
</template>
  
<script>
import { ref } from "vue";


export default {
    name: "Nav",
    setup() {
        let showMenu = ref(false);
        const toggleNav = () => (showMenu.value = !showMenu.value);
        return { showMenu, toggleNav };
    },
    props: ["showExtra"],

    mounted() {
        console.log(this.$root);
    },

};

</script>
  
<style lang="css">
.scale-slide-enter-active,
.scale-slide-leave-active {
    position: fixed;
    transition: all 0.85s ease;
}

.scale-slide-enter-from {
    left: -100%;
}

.scale-slide-enter-to {
    left: 0%;
}

.scale-slide-leave-from {
    transform: scale(1);
}

.scale-slide-leave-to {
    transform: scale(0.8);
}
</style>
  