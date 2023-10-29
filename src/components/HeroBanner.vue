<script setup>
// Social Links - Update this links to your link
const FacebookLink = 'https://www.facebook.com/itsarielbatoon';
const LinkedinLink = 'https://www.linkedin.com/in/ariel-batoon-679688286/';
const GithubLink = 'https://github.com/arielbatoon09';


</script>

<template>
    <section class="flex flex-col justify-between gap-6 sm:gap-10 md:gap-16 lg:flex-row py-16">
        <!-- content - start -->
        <div class="flex flex-col justify-between xl:w-5/12">
            <div></div>

            <div class="sm:text-center lg:py-12 lg:text-left xl:py-24">
                <p class="mb-4 font-semibold text-gray-600 md:mb-6 md:text-lg xl:text-xl">Getting to know</p>

                <h1 class="mb-8 text-4xl font-bold text-cyan-700 sm:text-5xl md:mb-12">Lorem ipsum dolor sit, amet consectetur adipisicing elit.</h1>

                <div class="flex flex-col gap-2.5 sm:flex-row sm:justify-center lg:justify-start">
                    <router-link to="/contact" href="#"
                        class="inline-block rounded-lg bg-cyan-700 px-8 py-3 text-center text-sm font-semibold text-white outline-none 
                        ring-indigo-300 transition duration-100 hover:bg-cyan-600 focus-visible:ring active:bg-cyan-700 md:text-base">
                        About Me
                    </router-link>

                    <router-link to="/contact"
                        class="inline-block rounded-lg bg-gray-200 px-8 py-3 text-center text-sm font-semibold text-gray-500 outline-none 
                        ring-indigo-300 transition duration-100 hover:bg-gray-300 focus-visible:ring active:text-gray-700 md:text-base">
                        Contact Me
                    </router-link>
                </div>
            </div>

            <!-- Social Media -->
            <div class="mt-8 flex items-center justify-center gap-4 sm:mt-16 lg:justify-start">
                <span class="text-sm font-semibold uppercase tracking-widest text-gray-400 sm:text-base">Social</span>
                <span class="h-px w-12 bg-gray-200"></span>

                <div class="flex gap-4">
                    <a :href="FacebookLink" target="_blank" 
                        class="text-gray-400 transition duration-100 hover:text-gray-500 active:text-gray-600">
                        <svg class="h-5 w-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg"
                            fill="currentColor" viewBox="0 0 8 19">
                            <path fill-rule="evenodd"
                                d="M6.135 3H8V0H6.135a4.147 4.147 0 0 0-4.142 4.142V6H0v3h2v9.938h3V9h2.021l.592-3H5V3.591A.6.6 0 0 1 5.592 3h.543Z"
                                clip-rule="evenodd" />
                        </svg>
                    </a>

                    <a :href="LinkedinLink" target="_blank"
                        class="text-gray-400 transition duration-100 hover:text-gray-500 active:text-gray-600">
                        <svg class="h-5 w-5" width="24" height="24" viewBox="0 0 24 24" fill="currentColor"
                            xmlns="http://www.w3.org/2000/svg">
                            <path
                                d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z" />
                        </svg>
                    </a>

                    <a :href="GithubLink" target="_blank"
                        class="text-gray-400 transition duration-100 hover:text-gray-500 active:text-gray-600">
                        <svg class="h-5 w-5" width="24" height="24" viewBox="0 0 24 24" fill="currentColor"
                            xmlns="http://www.w3.org/2000/svg">
                            <path
                                d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z" />
                        </svg>
                    </a>
                </div>
            </div>
        </div>
        <div class="h-48 overflow-hidden rounded-lg bg-gray-100 shadow-lg lg:h-auto xl:w-5/12">
            <img src="https://images.unsplash.com/photo-1618005198919-d3d4b5a92ead?auto=format&q=75&fit=crop&w=1000"
                loading="lazy" alt="Photo by Fakurian Design" class="h-full w-full object-cover object-center" />
        </div>
    </section>
</template>