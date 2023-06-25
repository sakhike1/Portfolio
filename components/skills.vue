<template>
    <div class=" bg-slate-900 pt-20">
        <section>
            <div class="mx-auto max-w-screen-xl px-4 py-16 sm:px-6 sm:py-24 lg:px-8">
                <div class="max-w-3xl">
                    <h2 data-aos="fade-right" data-aos-duration="3000" class="text-3xl text-white font-bold sm:text-4xl">
                        Process and guidelines that i like to follow to understand the clients needs
                    </h2>
                </div>

                <div class="mt-8 grid grid-cols-1 gap-8 lg:grid-cols-2 lg:gap-16">
                    <div class="relative  h-full w-full">
                        <img id="floating" alt="Party" src="~/assets/working.png"
                            class="absolute inset-0 h-[300px] w-full object-fit" />
                    </div>

                    <div class="lg:py-16">
                        <article class="space-y-4 text-gray-300">
                            <p>
                                As a UI designer, following a systematic process helps ensure the effectiveness and success
                                of your design efforts.

                            </p>

                            <p class="text-xs text-gray-400">
                                1. Gather information about the project, its goals, and target audience 2. Conduct research
                                to understand user needs, preferences, and behaviors. 3. Define project objectives,
                                constraints, and desired outcomes.4. Gather information about the project, its goals, and
                                target audience 5. Create user personas that represent the target audience.




                            </p>




                        </article>
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
</style>