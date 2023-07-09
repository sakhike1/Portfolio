<template>
    <div class="">
        <header class="">
            <div class="px-4 mx-auto sm:px-6 lg:px-8">

            </div>
        </header>

        <section data-aos="fade-right" data-aos-duration="3000" class="py-10 sm:py-16 lg:py-24">
            <div class="px-4 mx-auto max-w-7xl sm:px-6 lg:px-8">
                <div class="grid items-center grid-cols-1 gap-12 lg:grid-cols-2">
                    <div>
                        <h1 class="text-4xl font-bold text-black sm:text-6xl lg:text-3xl">
                            <p>
                                As a UI designer, following a systematic process helps ensure the effectiveness and success
                                of your design efforts.

                            </p>
                        </h1>


                        <p class="text-xs text-gray-400 pt-2">
                            1. Gather information about the project, its goals, and target audience 2. Conduct research
                            to understand user needs, preferences, and behaviors. 3. Define project objectives,
                            constraints, and desired outcomes.4. Gather information about the project, its goals, and
                            target audience 5. Create user personas that represent the target audience.




                        </p>

                        <div class="mt-10 sm:flex sm:items-center sm:space-x-8">
                            <a href="https://dribbble.com/shots/21900897-bloggers" title=""
                                class="inline-flex items-center justify-center px-10 py-4 text-base font-semibold text-white transition-all duration-200 bg-orange-500 hover:bg-orange-600 focus:bg-orange-600"
                                role="button"> Start exploring </a>


                        </div>
                    </div>

                    <div>
                        <img id="floating" alt="Party" src="~/assets/working.png">
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
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
</style>