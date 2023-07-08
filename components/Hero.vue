<template>
    <div class="py-16 bg-blue-100">
        <div class="xl:container m-auto px-6 text-gray-600 md:px-12 xl:px-16">
            <div data-aos="fade-down" data-aos-easing="linear" data-aos-duration="1500"
                class=" dark:lg:bg-darker lg:p-16 rounded-[4rem] space-y-6 md:flex md:gap-6 justify-center md:space-y-0 lg:items-center">
                <div class="md:5/12 lg:w-1/2">
                    <img class="sm:p-10 sm:h-full" id="floating" src="~/assets/3516822-removebg-preview.png" alt="image"
                        loading="lazy" width="" height="" />
                </div>
                <div class="md:7/12 lg:w-1/2">
                    <h2 id="box" class="text-3xl font-bold text-black md:text-4xl dark:text-white">
                        i like to Continuously learn and stay updated on the latest UI design trends
                    </h2>
                    <p class="my-8 text-xs text-gray-400 dark:text-gray-300">
                        With every project, i always demonstrates an unwavering
                        commitment to pushing the boundaries of design, transforming ideas
                        into extraordinary digital experiences that captivate and inspire.
                    </p>


                    <a href="https://deams-sakhike1.vercel.app/" title=""
                        class="inline-flex items-center justify-center px-8 py-4 mt-4 text-base font-semibold text-white transition-all duration-200 bg-gradient-to-b from-gray-900 to-gray-600  rounded-md hover:opacity-80 focus:opacity-80"
                        role="button"> Learn more</a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>

import AOS from "aos";
import "aos/dist/aos.css";
export default {

    mounted() {
        AOS.init({});

        let box2 = ["i like to Continuously learn and stay updated on the latest UI design trends", "Implementing sustainability into digital products should happen throughout the design process", "Create resources fully adapted to everyday life by incorporating inclusive design"]
        let box = document.getElementById("box");

        function random1() {
            let random = [Math.floor(Math.random() * box2.length)]
            box.textContent = box2[random]
            console.log(random1())



        }
        setInterval(random1, 5000);

    },




};


</script>
<style lang="scss" scoped>
#floating {
    animation-name: floating;
    animation-duration: 3s;
    animation-iteration-count: infinite;
    animation-timing-function: ease-in-out;
    margin-left: 30px;
    margin-top: 5px;
}

@keyframes floating {
    0% {
        transform: translate(0, 0px);
    }

    50% {
        transform: translate(0, 15px);
    }

    100% {
        transform: translate(0, -0px);
    }
}




@media screen and (max-width: 375px) and (min-width: 667px) {
    .text-center {
        text-align: left;
        margin: 20px 0 0;
    }

    img {
        display: none;
    }
}
</style>