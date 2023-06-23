<template>
    <div class="py-16 bg-black">
        <div class="xl:container m-auto px-6 text-gray-600 md:px-12 xl:px-16">
            <div
                class=" dark:lg:bg-darker lg:p-16 rounded-[4rem] space-y-6 md:flex md:gap-6 justify-center md:space-y-0 lg:items-center">
                <div class="md:5/12 lg:w-1/2">
                    <img id="floating" src="~/assets/3516822-removebg-preview.png" alt="image" loading="lazy" width=""
                        height="" />
                </div>
                <div class="md:7/12 lg:w-1/2">
                    <h2 class="text-3xl font-bold text-white md:text-4xl dark:text-white">
                        i like to Continuously learn and stay updated on the latest UI design trends
                    </h2>
                    <p class="my-8 text-gray-400 dark:text-gray-300">
                        With every project, i always demonstrates an unwavering
                        commitment to pushing the boundaries of design, transforming ideas
                        into extraordinary digital experiences that captivate and inspire.
                    </p>

                    <a href="https://deams-sakhike1.vercel.app/"
                        class="relative flex h-12 w-full items-center justify-center px-8 before:absolute before:inset-0  before:bg-sky-100 before:bg-gradient-to-b before:transition before:duration-300 hover:before:scale-105 active:duration-75 active:before:scale-95 dark:before:border-gray-700 dark:before:bg-gray-800 sm:w-max">
                        <span class="relative text-base font-semibold text-sky-600 dark:text-white">Learn More </span>
                    </a>
                </div>
            </div>
        </div>
    </div>
    <Work />
</template>

<script>
export default {

}
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
}</style>