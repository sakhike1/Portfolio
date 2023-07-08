<template>
    <div id="col">
        <section class="pt-10  bg-blue-50  py-10  2xl:py-24  sm:pt-16 md:pt-0">
            <div class="px-4 mx-auto rounded-md bg-gradient-to-r from-rose-100 to-teal-100 max-w-7xl  sm:px-6 lg:px-8">
                <div class="2xl:pl-24" data-aos="fade-right" data-aos-duration="3000">
                    <div class="grid grid-cols-1 gap-y-12 md:grid-cols-2 md:gap-x-8 2xl:gap-x-20">
                        <div class="span_3_of_3 text-center md:py-16 xl:py-24 md:text-left">
                            <blockquote>
                                <p class="text-sm sm:text-left  font-semibold leading-relaxed text-gray-500">
                                    Its always a good experience to work with sakhile he communicates effectively and is
                                    always
                                    willing to adjust to any changes that are sometimes unforeseen</p>
                            </blockquote>
                            <div class=".span_2_of_3 mt-6 sm:flex sm:items-baseline sm:justify-center md:justify-start">
                                <p class="text-base font-semibold text-gray-900">Ntonkozo Skhosana</p>
                                <p class="mt-2 text-base text-gray-700 sm:mt-0 sm:ml-2">Project Manager at Deams</p>
                            </div>
                            <a href="https://dribbble.com/shots/16443982-Landing-Page-with-Animation" title=""
                                class="inline-flex items-center justify-center px-8 py-4 mt-4 text-base font-semibold text-white transition-all duration-200 bg-gradient-to-b from-gray-900 to-gray-600  rounded-md hover:opacity-80 focus:opacity-80"
                                role="button"> View my work </a>

                        </div>

                        <div class="span_1_of_3  relative ">
                            <img class="md:absolute md:bottom-0 md:scale-110 md:origin-bottom-right lg:scale-75 2xl:scale-100 2xl:-mt-20"
                                src="https://cdn.rareblocks.xyz/collection/celebration/images/cta/11/smiling-man.png"
                                alt="" />
                        </div>
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

@media only screen and (max-width: 375px) {
    #floating {
        display: none;
    }
}
</style>