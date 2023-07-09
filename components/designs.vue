<template>
    <div class="py-30 ">
        <div class="xl:container  m-auto px-6 text-gray-600 md:px-12 xl:px-6">
            <div class="mb-12 py-20 space-y-2 text-center">
                <h1 class="text-3xl font-bold text-gray-800 sm:text-4xl dark:text-white">
                    Some of my recent work
                </h1>
                <p class="mt-3 text-gray-600 dark:text-gray-400">
                    design is a strong desire to create
                </p>
            </div>
            <div data-aos="fade-down" data-aos-easing="linear" data-aos-duration="1500"
                class="grid gap-8 md:grid-cols-2 lg:grid-cols-3">
                <div
                    class="group p-6 sm:p-8 rounded-3xl bg-gray-300 border border-gray-100 dark:shadow-none dark:border-gray-700 dark:bg-gray-800 bg-opacity-50 shadow-2xl shadow-gray-600/10">
                    <div class="relative overflow-hidden rounded-xl">
                        <img src="~/assets/Thumbnail.jpg" loading="lazy" width="1000" height="667"
                            class="h-64 w-full object-cover object-top transition duration-500 group-hover:scale-105" />
                    </div>
                    <div class="mt-6 relative">

                        <nuxt-link href="https://dribbble.com/shots/21904754-flat-iphone"
                            class="relative inline-flex items-center justify-start inline-block px-5 py-3 overflow-hidden font-bold rounded-full group">
                            <span
                                class="w-32 h-32 rotate-45 translate-x-12 -translate-y-2 absolute left-0 top-0 bg-white opacity-[3%]"></span>
                            <span
                                class="absolute top-0 left-0 w-48 h-48 -mt-1 transition-all duration-500 ease-in-out rotate-45 -translate-x-56 -translate-y-24 bg-white opacity-100 group-hover:-translate-x-8"></span>
                            <span
                                class="relative w-full text-left text-gray-400 transition-colors duration-200 ease-in-out group-hover:text-black-200">View
                                work
                            </span>
                            <span class="absolute inset-0 border-2 border-white rounded-full"></span>
                        </nuxt-link>
                    </div>

                </div>
                <div
                    class="group p-6 sm:p-8 rounded-3xl bg-gray-300 border border-gray-100 dark:shadow-none dark:border-gray-700 dark:bg-gray-800 bg-opacity-50 shadow-2xl shadow-gray-600/10">
                    <div class="relative overflow-hidden rounded-xl">
                        <img src="~/assets/Home.png" loading="lazy" width="1000" height="667"
                            class="h-64 w-full object-cover object-top transition duration-500 group-hover:scale-105" />
                    </div>
                    <div class="mt-6 relative">

                        <nuxt-link href="https://dribbble.com/shots/21904926-landing-page"
                            class="relative inline-flex items-center justify-start inline-block px-5 py-3 overflow-hidden font-bold rounded-full group">
                            <span
                                class="w-32 h-32 rotate-45 translate-x-12 -translate-y-2 absolute left-0 top-0 bg-white opacity-[3%]"></span>
                            <span
                                class="absolute top-0 left-0 w-48 h-48 -mt-1 transition-all duration-500 ease-in-out rotate-45 -translate-x-56 -translate-y-24 bg-white opacity-100 group-hover:-translate-x-8"></span>
                            <span
                                class="relative w-full text-left text-gray-400 transition-colors duration-200 ease-in-out group-hover:text-black-200">View
                                work
                            </span>
                            <span class="absolute inset-0 border-2 border-white rounded-full"></span>
                        </nuxt-link>
                    </div>

                </div>
                <div
                    class="group p-6 sm:p-8 rounded-3xl bg-gray-300 border border-gray-100 dark:shadow-none dark:border-gray-700 dark:bg-gray-800 bg-opacity-50 shadow-2xl shadow-gray-600/10">
                    <div class="relative overflow-hidden rounded-xl">
                        <img src="~/assets/phone.png" loading="lazy" width="1000" height="667"
                            class="h-64 w-full object-fit object-top transition duration-500 group-hover:scale-105" />
                    </div>
                    <div class="mt-6 relative">

                        <nuxt-link href="https://dribbble.com/shots/21904516-Watch-app"
                            class="relative inline-flex items-center justify-start inline-block px-5 py-3 overflow-hidden font-bold rounded-full group">
                            <span
                                class="w-32 h-32 rotate-45 translate-x-12 -translate-y-2 absolute left-0 top-0 bg-white opacity-[3%]"></span>
                            <span
                                class="absolute top-0 left-0 w-48 h-48 -mt-1 transition-all duration-500 ease-in-out rotate-45 -translate-x-56 -translate-y-24 bg-white opacity-100 group-hover:-translate-x-8"></span>
                            <span
                                class="relative w-full text-left text-gray-400 transition-colors duration-200 ease-in-out group-hover:text-black-200">View
                                work
                            </span>
                            <span class="absolute inset-0 border-2 border-white rounded-full"></span>
                        </nuxt-link>
                    </div>

                </div>
            </div>
        </div>
    </div>
    <Moredesign />
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped></style>