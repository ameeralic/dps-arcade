<template>
    <div class="min-h-screen">
        <!-- Hero Section  -->
        <section class="bg-white dark:bg-gray-900">
            <div class="grid max-w-screen-xl mx-auto gap-4 xl:gap-10 lg:py-16 lg:grid-cols-12">

                <div class="mr-auto place-self-center lg:col-span-7 pt-2 md:py-32 order-2 px-4">
                    <h1
                        class="max-w-2xl font-dps mb-4 text-5xl text-center md:text-left font-extrabold tracking-tight text-primary-700 leading-none md:text-5xl xl:text-6xl dark:text-white">
                        <span
                            class="text-3xl font-extrabold tracking-tight text-primary-700 leading-none md:text-4xl xl:text-4xl dark:text-white">Welcome
                            to </span> <br />DPS Arcade
                    </h1>
                    <p
                        class="max-w-2xl text-center md:text-left mb-2 font-medium text-gray-500 lg:mb-4 md:text-lg lg:text-xl dark:text-gray-400">
                        Looking for Men's PG near CUSAT ?.
                    <p
                        class="max-w-2xl mb-6 font-light text-center md:text-left text-gray-500 lg:mb-8 md:text-md lg:text-md dark:text-gray-400">
                        Here, in DPS Aracde we provide
                        <span class="font-medium text-blue-600">Single/Double rooms with attached bathroom</span> for men
                        for monthly
                        rent.
                    </p>
                    </p>
                    <div class="text-center md:text-left mb-4">
                        <Link href="/contact"
                            class="inline-flex mb-3  items-center justify-center px-5 py-3 mr-3 text-base font-medium text-center text-white rounded-lg bg-primary-700 hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 dark:focus:ring-primary-900">
                        Check Availablity
                        <svg class="w-5 h-5 ml-2 -mr-1" fill="currentColor" viewBox="0 0 20 20"
                            xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd"
                                d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
                                clip-rule="evenodd"></path>
                        </svg>
                        </Link>
                        <Link href="/hotel-deluxe"
                            class="inline-flex items-center justify-center px-5 py-3 text-base font-medium text-center text-gray-900 border border-gray-300 rounded-lg hover:bg-gray-100 focus:ring-4 focus:ring-gray-100 dark:text-white dark:border-gray-700 dark:hover:bg-gray-700 dark:focus:ring-gray-800">
                        Join Mess Service
                        </Link>
                    </div>

                </div>
                <div class="lg:mt-0 lg:col-span-5 lg:flex">
                    <img :src="'/assets/img/dps-hero.jpg'" class="h-48 md:h-full w-full object-cover" alt="mockup">
                </div>
            </div>
        </section>

        <!-- highlights Section  -->
        <section class="bg-white dark:bg-gray-900">
            <div class="max-w-screen-xl px-4 py-8 mx-auto text-center lg:py-16 lg:px-6">
                <div
                    class="grid max-w-screen-sm justify-center gap-4 sm:grid-cols-2 mx-auto text-gray-900 dark:text-white mb-8">
                    <div class="flex gap-2">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd"
                                d="M11.54 22.351l.07.04.028.016a.76.76 0 00.723 0l.028-.015.071-.041a16.975 16.975 0 001.144-.742 19.58 19.58 0 002.683-2.282c1.944-1.99 3.963-4.98 3.963-8.827a8.25 8.25 0 00-16.5 0c0 3.846 2.02 6.837 3.963 8.827a19.58 19.58 0 002.682 2.282 16.975 16.975 0 001.145.742zM12 13.5a3 3 0 100-6 3 3 0 000 6z"
                                clip-rule="evenodd" />
                        </svg>
                        <dd class="font-light text-gray-500 dark:text-gray-400 text-left">Near Dreamflower Akademia
                            Apartments,
                            <br />Thirunilath
                            Road, CUSAT<br />South Kalamassery, Kochi-22
                        </dd>
                    </div>
                    <div>
                        <ul class="text-left text-primary-600 font-bold">
                            <li>~ 300m to CUSAT</li>
                            <li>~ 700m to CUSAT Metro Station</li>
                            <li>~ 3.5km to Lulu mall</li>
                        </ul>
                    </div>
                </div>
                <!-- <dl class="grid max-w-screen-md gap-8 mx-auto text-gray-900 sm:grid-cols-3 dark:text-white mb-4 md:mb-8">
                    <div class="flex flex-col items-center justify-center">
                        <dt class="mb-2 text-3xl md:text-4xl font-extrabold">200+</dt>
                        <dd class="font-light text-gray-500 dark:text-gray-400">Happy customers</dd>
                    </div>
                    <div class="flex flex-col items-center justify-center">
                        <dt class="mb-2 text-3xl md:text-4xl font-extrabold">50+</dt>
                        <dd class="font-light text-gray-500 dark:text-gray-400">Beds</dd>
                    </div>
                    <div class="flex flex-col items-center justify-center">
                        <dt class="mb-2 text-3xl md:text-4xl font-extrabold">10Y+</dt>
                        <dd class="font-light text-gray-500 dark:text-gray-400">Experience</dd>
                    </div>

                </dl> -->

            </div>
        </section>

        <!-- Features Section  -->
        <section class="bg-white dark:bg-gray-900">
            <div class="py-8 px-4 mx-auto max-w-screen-xl sm:py-16 lg:px-6">
                <div class="max-w-screen-md mb-8 lg:mb-16">
                    <h2 class="mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-white">Feel Home with Us
                    </h2>
                    <p class="text-gray-500 sm:text-xl dark:text-gray-400">
                        With over a decade of dedicated experience, we take pride in
                        providing a warm and welcoming home away from home for our residents. Boasting a satisfied clientele
                        of 200+ happy customers, we have established ourselves as a trusted name in the industry.</p>
                </div>
                <div class="grid grid-cols-2 gap-8 lg:grid-cols-3 md:gap-12 md:space-y-0">
                    <div>
                        <div
                            class="flex justify-center items-center mb-4 w-10 h-10 rounded-full bg-primary-100 lg:h-12 lg:w-12 dark:bg-primary-900">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"
                                class="w-5 h-5 text-primary-600 lg:w-6 lg:h-6 dark:text-primary-300">
                                <path
                                    d="M11.47 3.84a.75.75 0 011.06 0l8.69 8.69a.75.75 0 101.06-1.06l-8.689-8.69a2.25 2.25 0 00-3.182 0l-8.69 8.69a.75.75 0 001.061 1.06l8.69-8.69z" />
                                <path
                                    d="M12 5.432l8.159 8.159c.03.03.06.058.091.086v6.198c0 1.035-.84 1.875-1.875 1.875H15a.75.75 0 01-.75-.75v-4.5a.75.75 0 00-.75-.75h-3a.75.75 0 00-.75.75V21a.75.75 0 01-.75.75H5.625a1.875 1.875 0 01-1.875-1.875v-6.198a2.29 2.29 0 00.091-.086L12 5.43z" />
                            </svg>


                        </div>
                        <h3 class="mb-2 text-xl font-bold dark:text-white">Single/Double Rooms</h3>
                        <p class="text-gray-500 dark:text-gray-400">We provide single/double rooms with up to three beds.
                        </p>
                    </div>
                    <div>
                        <div
                            class="flex justify-center items-center mb-4 w-10 h-10 rounded-full bg-primary-100 lg:h-12 lg:w-12 dark:bg-primary-900">
                            <svg xmlns="http://www.w3.org/2000/svg" height="1em" fill="currentColor"
                                class="w-5 h-5 text-primary-600 lg:w-6 lg:h-6 dark:text-primary-300"
                                viewBox="0 0 512 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                                <path
                                    d="M288 96c0-17.7 14.3-32 32-32s32 14.3 32 32s14.3 32 32 32s32-14.3 32-32c0-53-43-96-96-96s-96 43-96 96V288H160V264c0-30.9-25.1-56-56-56H56c-13.3 0-24 10.7-24 24s10.7 24 24 24h48c4.4 0 8 3.6 8 8v24H32c-17.7 0-32 14.3-32 32s14.3 32 32 32H256 480c17.7 0 32-14.3 32-32s-14.3-32-32-32H400V264c0-4.4 3.6-8 8-8h56c13.3 0 24-10.7 24-24s-10.7-24-24-24H408c-30.9 0-56 25.1-56 56v24H288V96zM480 416V384H32v32c0 53 43 96 96 96H384c53 0 96-43 96-96z" />
                            </svg>
                        </div>
                        <h3 class="mb-2 text-xl font-bold dark:text-white">Attached Bathroom</h3>
                        <p class="text-gray-500 dark:text-gray-400">All rooms have attached bathrooms with shower and
                            toilet.</p>
                    </div>

                    <div>
                        <div
                            class="flex justify-center items-center mb-4 w-10 h-10 rounded-full bg-primary-100 lg:h-12 lg:w-12 dark:bg-primary-900">
                            <svg xmlns="http://www.w3.org/2000/svg" height="1em"
                                class="w-5 h-5 text-primary-600 lg:w-6 lg:h-6 dark:text-primary-300" fill="currentColor"
                                viewBox="0 0 512 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                                <path
                                    d="M135.2 117.4L109.1 192H402.9l-26.1-74.6C372.3 104.6 360.2 96 346.6 96H165.4c-13.6 0-25.7 8.6-30.2 21.4zM39.6 196.8L74.8 96.3C88.3 57.8 124.6 32 165.4 32H346.6c40.8 0 77.1 25.8 90.6 64.3l35.2 100.5c23.2 9.6 39.6 32.5 39.6 59.2V400v48c0 17.7-14.3 32-32 32H448c-17.7 0-32-14.3-32-32V400H96v48c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32V400 256c0-26.7 16.4-49.6 39.6-59.2zM128 288a32 32 0 1 0 -64 0 32 32 0 1 0 64 0zm288 32a32 32 0 1 0 0-64 32 32 0 1 0 0 64z" />
                            </svg>
                        </div>
                        <h3 class="mb-2 text-xl font-bold dark:text-white">Car Parking</h3>
                        <p class="text-gray-500 dark:text-gray-400">We provide parking space your vehicles.</p>
                    </div>
                    <div>
                        <div
                            class="flex justify-center items-center mb-4 w-10 h-10 rounded-full bg-primary-100 lg:h-12 lg:w-12 dark:bg-primary-900">

                            <svg xmlns="http://www.w3.org/2000/svg" height="1em"
                                class="w-5 h-5 text-primary-600 lg:w-6 lg:h-6 dark:text-primary-300" fill="currentColor"
                                viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                                <path
                                    d="M349.4 44.6c5.9-13.7 1.5-29.7-10.6-38.5s-28.6-8-39.9 1.8l-256 224c-10 8.8-13.6 22.9-8.9 35.3S50.7 288 64 288H175.5L98.6 467.4c-5.9 13.7-1.5 29.7 10.6 38.5s28.6 8 39.9-1.8l256-224c10-8.8 13.6-22.9 8.9-35.3s-16.6-20.7-30-20.7H272.5L349.4 44.6z" />
                            </svg>
                        </div>
                        <h3 class="mb-2 text-xl font-bold dark:text-white">24/7 Power Supply</h3>
                        <p class="text-gray-500 dark:text-gray-400">With our inverter and solar system, we provide a
                            relaible
                            electric supply.</p>
                    </div>
                    <div>
                        <div
                            class="flex justify-center items-center mb-4 w-10 h-10 rounded-full bg-primary-100 lg:h-12 lg:w-12 dark:bg-primary-900">
                            <svg xmlns="http://www.w3.org/2000/svg" height="1em"
                                class="w-5 h-5 text-primary-600 lg:w-6 lg:h-6 dark:text-primary-300" fill="currentColor"
                                viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                                <path
                                    d="M416 0C400 0 288 32 288 176V288c0 35.3 28.7 64 64 64h32V480c0 17.7 14.3 32 32 32s32-14.3 32-32V352 240 32c0-17.7-14.3-32-32-32zM64 16C64 7.8 57.9 1 49.7 .1S34.2 4.6 32.4 12.5L2.1 148.8C.7 155.1 0 161.5 0 167.9c0 45.9 35.1 83.6 80 87.7V480c0 17.7 14.3 32 32 32s32-14.3 32-32V255.6c44.9-4.1 80-41.8 80-87.7c0-6.4-.7-12.8-2.1-19.1L191.6 12.5c-1.8-8-9.3-13.3-17.4-12.4S160 7.8 160 16V150.2c0 5.4-4.4 9.8-9.8 9.8c-5.1 0-9.3-3.9-9.8-9L127.9 14.6C127.2 6.3 120.3 0 112 0s-15.2 6.3-15.9 14.6L83.7 151c-.5 5.1-4.7 9-9.8 9c-5.4 0-9.8-4.4-9.8-9.8V16zm48.3 152l-.3 0-.3 0 .3-.7 .3 .7z" />
                            </svg>
                        </div>
                        <h3 class="mb-2 text-xl font-bold dark:text-white">Mess Service</h3>
                        <p class="text-gray-500 dark:text-gray-400">We provide mess service for our guests and outsiders.
                            3 times a day 6 days a week(sunday off).</p>
                    </div>
                    <div>
                        <div
                            class="flex justify-center items-center mb-4 w-10 h-10 rounded-full bg-primary-100 lg:h-12 lg:w-12 dark:bg-primary-900">
                            <svg xmlns="http://www.w3.org/2000/svg" height="1em"
                                class="w-5 h-5 text-primary-600 lg:w-6 lg:h-6 dark:text-primary-300" fill="currentColor"
                                viewBox="0 0 384 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                                <path
                                    d="M32 0C23.1 0 14.6 3.7 8.6 10.2S-.6 25.4 .1 34.3L28.9 437.7c3 41.9 37.8 74.3 79.8 74.3H275.3c42 0 76.8-32.4 79.8-74.3L383.9 34.3c.6-8.9-2.4-17.6-8.5-24.1S360.9 0 352 0H32zM73 156.5L66.4 64H317.6L311 156.5l-24.2 12.1c-19.4 9.7-42.2 9.7-61.6 0c-20.9-10.4-45.5-10.4-66.4 0c-19.4 9.7-42.2 9.7-61.6 0L73 156.5z" />
                            </svg>
                        </div>
                        <h3 class="mb-2 text-xl font-bold dark:text-white">Purified Drinking Water</h3>
                        <p class="text-gray-500 dark:text-gray-400">We have water purifier to serve hot/cold fresh water.
                        </p>
                    </div>
                    <div>
                        <div
                            class="flex justify-center items-center mb-4 w-10 h-10 rounded-full bg-primary-100 lg:h-12 lg:w-12 dark:bg-primary-900">
                            <svg xmlns="http://www.w3.org/2000/svg" height="1em"
                                class="w-5 h-5 text-primary-600 lg:w-6 lg:h-6 dark:text-primary-300" fill="currentColor"
                                viewBox="0 0 576 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                                <path
                                    d="M288 32c-80.8 0-145.5 36.8-192.6 80.6C48.6 156 17.3 208 2.5 243.7c-3.3 7.9-3.3 16.7 0 24.6C17.3 304 48.6 356 95.4 399.4C142.5 443.2 207.2 480 288 480s145.5-36.8 192.6-80.6c46.8-43.5 78.1-95.4 93-131.1c3.3-7.9 3.3-16.7 0-24.6c-14.9-35.7-46.2-87.7-93-131.1C433.5 68.8 368.8 32 288 32zM144 256a144 144 0 1 1 288 0 144 144 0 1 1 -288 0zm144-64c0 35.3-28.7 64-64 64c-7.1 0-13.9-1.2-20.3-3.3c-5.5-1.8-11.9 1.6-11.7 7.4c.3 6.9 1.3 13.8 3.2 20.7c13.7 51.2 66.4 81.6 117.6 67.9s81.6-66.4 67.9-117.6c-11.1-41.5-47.8-69.4-88.6-71.1c-5.8-.2-9.2 6.1-7.4 11.7c2.1 6.4 3.3 13.2 3.3 20.3z" />
                            </svg>
                        </div>
                        <h3 class="mb-2 text-xl font-bold dark:text-white">CCTV Secured</h3>
                        <p class="text-gray-500 dark:text-gray-400">24/7 cctv surveillance system.
                        </p>
                    </div>

                    <div>
                        <div
                            class="flex justify-center items-center mb-4 w-10 h-10 rounded-full bg-primary-100 lg:h-12 lg:w-12 dark:bg-primary-900">

                            <svg xmlns="http://www.w3.org/2000/svg" height="1em"
                                class="w-5 h-5 text-primary-600 lg:w-6 lg:h-6 dark:text-primary-300" fill="currentColor"
                                viewBox="0 0 640 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                                <path
                                    d="M168.8 462.3c-7.9-4-11.1-13.6-7.2-21.5L192 380.2l0-44.2c0-4.2 1.7-8.3 4.7-11.3L256 265.4V242.2L139.2 344C87.8 395.3 0 358.9 0 286.3c0-41.1 30.6-75.8 71.4-80.9l159.9-23.9-49.6-41.3c-5.1-4.2-7-11.1-4.9-17.4l13.9-41.7-29-58.1c-4-7.9-.7-17.5 7.2-21.5s17.5-.7 21.5 7.2l32 64c1.9 3.8 2.2 8.2 .9 12.2l-12.5 37.6L256 160.5V137.9c0-14.9 10.1-27.3 23.8-31V63.7c0-4.5 3.7-8.2 8.2-8.2s8.2 3.7 8.2 8.2V107c13.7 3.6 23.8 16.1 23.8 31v22.6l45.4-37.8L352.8 85.1c-1.3-4-1-8.4 .9-12.2l32-64c4-7.9 13.6-11.1 21.5-7.2s11.1 13.6 7.2 21.5l-29 58.1 13.9 41.7c2.1 6.2 .1 13.1-4.9 17.4l-49.6 41.3 159.9 23.9c22.5 2.8 41.8 14.6 54.7 31.4c-2.7 2.6-5.2 5.4-7.3 8.6c-8.6-12.9-23.3-21.5-40-21.5s-31.4 8.5-40 21.5c-8.6-12.9-23.3-21.5-40-21.5c-21.7 0-40 14.3-45.9 34.1c-10.7 3.2-19.8 10.1-25.9 19.2l-40.2-35v23.1l32.4 32.4c-.3 2-.4 4.1-.4 6.2c0 16.7 8.5 31.4 21.5 40c-4 2.6-7.5 5.9-10.6 9.5L320 310.6v50c0 17.7-14.3 32-32 32s-32-14.3-32-32v-50l-32 32 0 41.4c0 2.5-.6 4.9-1.7 7.2l-32 64c-4 7.9-13.6 11.1-21.5 7.2zM512 256c8.8 0 16 7.2 16 16v16h48V272c0-8.8 7.2-16 16-16s16 7.2 16 16v16h16c8.8 0 16 7.2 16 16s-7.2 16-16 16H608v48h16c8.8 0 16 7.2 16 16s-7.2 16-16 16H608v48h16c8.8 0 16 7.2 16 16s-7.2 16-16 16H608v16c0 8.8-7.2 16-16 16s-16-7.2-16-16V480H528v16c0 8.8-7.2 16-16 16s-16-7.2-16-16V480H448v16c0 8.8-7.2 16-16 16s-16-7.2-16-16V480H400c-8.8 0-16-7.2-16-16s7.2-16 16-16h16V400H400c-8.8 0-16-7.2-16-16s7.2-16 16-16h16V320H400c-8.8 0-16-7.2-16-16s7.2-16 16-16h16V272c0-8.8 7.2-16 16-16s16 7.2 16 16v16h48V272c0-8.8 7.2-16 16-16zm16 112h48V320H528v48zm0 80h48V400H528v48zM448 320v48h48V320H448zm0 80v48h48V400H448z" />
                            </svg>
                        </div>
                        <h3 class="mb-2 text-xl font-bold dark:text-white">Mosquito Free</h3>
                        <p class="text-gray-500 dark:text-gray-400">All windows and ventilations have mosquito net attached
                            to prevent bugs.</p>
                    </div>

                    <div>
                        <div
                            class="flex justify-center items-center mb-4 w-10 h-10 rounded-full bg-primary-100 lg:h-12 lg:w-12 dark:bg-primary-900">

                            <svg xmlns="http://www.w3.org/2000/svg" height="1em"
                                class="w-5 h-5 text-primary-600 lg:w-6 lg:h-6 dark:text-primary-300" fill="currentColor"
                                viewBox="0 0 640 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                                <path
                                    d="M211.8 0c7.8 0 14.3 5.7 16.7 13.2C240.8 51.9 277.1 80 320 80s79.2-28.1 91.5-66.8C413.9 5.7 420.4 0 428.2 0h12.6c22.5 0 44.2 7.9 61.5 22.3L628.5 127.4c6.6 5.5 10.7 13.5 11.4 22.1s-2.1 17.1-7.8 23.6l-56 64c-11.4 13.1-31.2 14.6-44.6 3.5L480 197.7V448c0 35.3-28.7 64-64 64H224c-35.3 0-64-28.7-64-64V197.7l-51.5 42.9c-13.3 11.1-33.1 9.6-44.6-3.5l-56-64c-5.7-6.5-8.5-15-7.8-23.6s4.8-16.6 11.4-22.1L137.7 22.3C155 7.9 176.7 0 199.2 0h12.6z" />
                            </svg>
                        </div>
                        <h3 class="mb-2 text-xl font-bold dark:text-white">Washing space</h3>
                        <p class="text-gray-500 dark:text-gray-400">We have roofed terrace with cloth washing and drying
                            spaces.</p>
                    </div>

                </div>
            </div>
        </section>

        <!-- Gallry Section   -->
        <section class="bg-white dark:bg-gray-900">
            <div class="py-8 px-4 mx-auto max-w-screen-xl sm:py-16 lg:px-6">
                <div class="max-w-screen-md mb-8 lg:mb-16">
                    <h2 class="mb-4 text-4xl tracking-tight font-extrabold text-center text-gray-900 dark:text-white">
                        Gallery
                    </h2>
                </div>
                <div class="grid grid-cols-2 md:grid-cols-3 gap-4">
                    <div>
                        <img class="h-auto max-w-full rounded-lg"
                            src="https://flowbite.s3.amazonaws.com/docs/gallery/square/image.jpg" alt="">
                    </div>
                    <div>
                        <img class="h-auto max-w-full rounded-lg"
                            src="https://flowbite.s3.amazonaws.com/docs/gallery/square/image-1.jpg" alt="">
                    </div>
                    <div>
                        <img class="h-auto max-w-full rounded-lg"
                            src="https://flowbite.s3.amazonaws.com/docs/gallery/square/image-2.jpg" alt="">
                    </div>
                    <div>
                        <img class="h-auto max-w-full rounded-lg"
                            src="https://flowbite.s3.amazonaws.com/docs/gallery/square/image-3.jpg" alt="">
                    </div>
                    <div>
                        <img class="h-auto max-w-full rounded-lg"
                            src="https://flowbite.s3.amazonaws.com/docs/gallery/square/image-4.jpg" alt="">
                    </div>
                    <div>
                        <img class="h-auto max-w-full rounded-lg"
                            src="https://flowbite.s3.amazonaws.com/docs/gallery/square/image-5.jpg" alt="">
                    </div>
                    <div>
                        <img class="h-auto max-w-full rounded-lg"
                            src="https://flowbite.s3.amazonaws.com/docs/gallery/square/image-6.jpg" alt="">
                    </div>
                    <div>
                        <img class="h-auto max-w-full rounded-lg"
                            src="https://flowbite.s3.amazonaws.com/docs/gallery/square/image-7.jpg" alt="">
                    </div>
                    <div>
                        <img class="h-auto max-w-full rounded-lg"
                            src="https://flowbite.s3.amazonaws.com/docs/gallery/square/image-8.jpg" alt="">
                    </div>
                    <div>
                        <img class="h-auto max-w-full rounded-lg"
                            src="https://flowbite.s3.amazonaws.com/docs/gallery/square/image-9.jpg" alt="">
                    </div>
                    <div>
                        <img class="h-auto max-w-full rounded-lg"
                            src="https://flowbite.s3.amazonaws.com/docs/gallery/square/image-10.jpg" alt="">
                    </div>
                    <div>
                        <img class="h-auto max-w-full rounded-lg"
                            src="https://flowbite.s3.amazonaws.com/docs/gallery/square/image-11.jpg" alt="">
                    </div>
                </div>

            </div>


        </section>



        <!-- Tesimonials Section   -->
        <section class="bg-white dark:bg-gray-900">
            <div class="py-8 px-4 mx-auto max-w-screen-xl text-center lg:py-16 lg:px-6">
                <div class="mx-auto max-w-screen-sm">
                    <h2 class="mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-white">Testimonials</h2>
                    <p class="mb-8 font-light text-gray-500 lg:mb-16 sm:text-xl dark:text-gray-400">For the last 10+ years
                        we made 200+ happy faces. Hear what they say.
                    </p>
                </div>
                <div class="grid mb-8 lg:mb-12 lg:grid-cols-2">
                    <figure
                        class="flex flex-col justify-center items-center p-8 text-center bg-gray-50 border-b border-gray-200 md:p-12 lg:border-r dark:bg-gray-800 dark:border-gray-700">
                        <blockquote class="mx-auto mb-8 max-w-2xl text-gray-500 dark:text-gray-400">
                            <h3 class="text-lg font-semibold text-gray-900 dark:text-white">Staying at DPS Arcade has been
                                an absolute delight.</h3>
                            <p class="my-4">"The single room with an attached bath provided me with the perfect blend of
                                privacy and comfort. The affordability is unmatched, and the amenities like 24x7 power
                                supply and purified water made my stay incredibly convenient. </p>
                            <p class="my-4">The friendly atmosphere and proximity to the university and metro station were
                                the icing on the cake. Highly recommended!"
                            </p>
                        </blockquote>
                        <figcaption class="flex justify-center items-center space-x-3">
                            <img class="w-9 h-9 rounded-full"
                                src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/avatars/karen-nelson.png"
                                alt="profile picture">
                            <div class="space-y-0.5 font-medium dark:text-white text-left">
                                <div>Ameerali C</div>
                                <div class="text-sm font-light text-gray-500 dark:text-gray-400">Student at CUSAT</div>
                            </div>
                        </figcaption>
                    </figure>
                    <figure
                        class="flex flex-col justify-center items-center p-8 text-center bg-gray-50 border-b border-gray-200 md:p-12 dark:bg-gray-800 dark:border-gray-700">
                        <blockquote class="mx-auto mb-8 max-w-2xl text-gray-500 dark:text-gray-400">
                            <h3 class="text-lg font-semibold text-gray-900 dark:text-white">I have been a satisfied resident
                                of DPS Arcade for the past two years.
                            </h3>
                            <p class="my-4">"The double room accommodation exceeded my expectations in terms of both space
                                and cleanliness.</p>
                            <p class="my-4">The car parking facility eased my worries about vehicle safety, and the CCTV
                                surveillance system added an extra layer of security. It truly is the most budget-friendly
                                paying guest service I've come across in Kochi."</p>
                        </blockquote>
                        <figcaption class="flex justify-center items-center space-x-3">
                            <img class="w-9 h-9 rounded-full"
                                src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/avatars/roberta-casas.png"
                                alt="profile picture">
                            <div class="space-y-0.5 font-medium dark:text-white text-left">
                                <div>Arun Gopinath</div>
                                <div class="text-sm font-light text-gray-500 dark:text-gray-400">Staff at CUSAT
                                </div>
                            </div>
                        </figcaption>
                    </figure>
                    <figure
                        class="flex flex-col justify-center items-center p-8 text-center bg-gray-50 border-b border-gray-200 lg:border-b-0 md:p-12 lg:border-r dark:bg-gray-800 dark:border-gray-700">
                        <blockquote class="mx-auto mb-8 max-w-2xl text-gray-500 dark:text-gray-400">
                            <h3 class="text-lg font-semibold text-gray-900 dark:text-white">As a parent, safety and comfort
                                were my top priorities when searching for accommodation for my son in Kochi. </h3>
                            <p class="my-4">"DPS Arcade not only met but exceeded these expectations. The open terrace with
                                washing space was a unique and thoughtful feature, and the attentive staff created a warm
                                and homely environment. </p>
                            <p class="my-4">I couldn't have asked for a better place for my son to stay during his
                                university years."</p>
                        </blockquote>
                        <figcaption class="flex justify-center items-center space-x-3">
                            <img class="w-9 h-9 rounded-full"
                                src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/avatars/jese-leos.png"
                                alt="profile picture">
                            <div class="space-y-0.5 font-medium dark:text-white text-left">
                                <div>Abdul Karim C</div>
                                <div class="text-sm font-light text-gray-500 dark:text-gray-400">Parent</div>
                            </div>
                        </figcaption>
                    </figure>
                    <figure
                        class="flex flex-col justify-center items-center p-8 text-center bg-gray-50 border-gray-200 md:p-12 dark:bg-gray-800 dark:border-gray-700">
                        <blockquote class="mx-auto mb-8 max-w-2xl text-gray-500 dark:text-gray-400">
                            <h3 class="text-lg font-semibold text-gray-900 dark:text-white">DPS Arcade made my transition to
                                a new city seamless and stress-free. </h3>
                            <p class="my-4">"The convenient location within walking distance of the metro station was a
                                game-changer for my daily commute. The uninterrupted power supply ensured I never faced any
                                disruptions while working from home.</p>
                            <p class="my-4">The team's hospitality and the array of amenities provided truly made me feel
                                like a valued resident."</p>
                        </blockquote>
                        <figcaption class="flex justify-center items-center space-x-3">
                            <img class="w-9 h-9 rounded-full"
                                src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/avatars/joseph-mcfall.png"
                                alt="profile picture">
                            <div class="space-y-0.5 font-medium dark:text-white text-left">
                                <div>Rafeeq</div>
                                <div class="text-sm font-light text-gray-500 dark:text-gray-400">Working Professional</div>
                            </div>
                        </figcaption>
                    </figure>
                </div>
            </div>
        </section>
    </div>
</template>
<script>
</script>
