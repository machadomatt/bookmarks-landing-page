<template>
    <header>
        <nav class="container flex items-center py-4 mt-4 sm:mt-12">
            <div class="py-1">
                <img src="./assets/img/logo-bookmark.svg" alt="Bookmarks" />
            </div>
            <ul
                class="
                    hidden
                    flex-1
                    justify-end
                    items-center
                    gap-12
                    text-bookmark-blue
                    uppercase
                    text-sm
                    sm:flex
                "
            >
                <li class="cursor-pointer">
                    <a
                        class="
                            transition
                            outline-none
                            hover:text-bookmark-red
                            focus:text-bookmark-red
                        "
                        href="#features"
                        >Features</a
                    >
                </li>
                <li class="cursor-pointer">
                    <a
                        class="
                            transition
                            outline-none
                            hover:text-bookmark-red
                            focus:text-bookmark-red
                        "
                        href="#faq"
                        >FAQ</a
                    >
                </li>
                <li class="cursor-pointer">
                    <a
                        class="
                            transition
                            outline-none
                            hover:text-bookmark-red
                            focus:text-bookmark-red
                        "
                        href="#contact"
                        >Contact</a
                    >
                </li>
                <button
                    type="button"
                    class="
                        btn
                        bg-bookmark-red
                        text-white
                        uppercase
                        outline-none
                        focus:bg-bookmark-white focus:text-black
                        hover:bg-bookmark-white hover:text-black
                    "
                >
                    Login
                </button>
            </ul>
            <div class="flex flex-1 justify-end sm:hidden">
                <svg
                    xmlns="http://www.w3.org/2000/svg"
                    aria-hidden="true"
                    focusable="false"
                    class="w-6 h-6 text-bookmark-blue"
                    role="img"
                    viewBox="0 0 448 512"
                >
                    <path
                        fill="currentColor"
                        d="M16 132h416c8.837 0 16-7.163 16-16V76c0-8.837-7.163-16-16-16H16C7.163 60 0 67.163 0 76v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16z"
                    />
                </svg>
            </div>
        </nav>
    </header>

    <section class="relative">
        <div class="container flex flex-col-reverse items-center gap-12 mt-14 lg:flex-row lg:mt-28">
            <div class="flex flex-1 flex-col items-center lg:items-start">
                <h2
                    class="
                        text-bookmark-blue text-3xl text-center
                        mb-6
                        md:text-4xl
                        lg:text-left lg:text-5xl
                    "
                >
                    A Simple Bookmark Manager
                </h2>
                <p class="text-bookmark-grey text-lg mb-6 text-center lg:text-left">
                    A clean and simple interface to organize your favourite websites. Open a new
                    browser tab and see your sites load instantly. Try it for free.
                </p>
                <div class="flex justify-center flex-wrap gap-6">
                    <button type="button" class="btn btn-purple">Get it on Chrome</button>
                    <button type="button" class="btn btn-white">Get it on Firefox</button>
                </div>
            </div>
            <div class="flex justify-center flex-1 mb-10 z-10 md:mb-16 lg:mb-0">
                <img
                    class="w-5/6 h-5/6 sm:w-3/4 sm:h-3/4 md:w-full md:h-full"
                    src="./assets/img/hero-bg.png"
                    alt="A Simple Bookmark Manager"
                />
            </div>
        </div>
        <div
            class="
                hidden
                overflow-hidden
                bg-bookmark-purple
                rounded-l-full
                absolute
                h-80
                w-2/4
                top-32
                right-0
                md:block
                lg:-bottom-28 lg:-right-36
            "
        ></div>
    </section>

    <section id="features" class="bg-bookmark-white py-20 mt-20 lg:mt-60">
        <div class="mx-auto px-2 sm:w-3/4 lg:w-5/12">
            <h1 class="text-3xl text-center text-bookmark-blue">Features</h1>
            <p class="text-center text-bookmark-grey mt-4">
                Our aim is to make it quick and easy for you to access your favourite websites. Your
                bookmarks sync between your devices so you can access them on the go.
            </p>
        </div>
        <div class="relative mt-20 lg:mt-24">
            <div class="container flex flex-col items-center justify-center gap-x-24 lg:flex-row">
                <div class="flex flex-1 justify-center z-10 mb-10 lg:mb-0">
                    <img
                        class="w-5/6 h-5/6 sm:w-3/4 sm:h-3/4 md:w-full md:h-full"
                        src="./assets/img/illustration-features-tab-1.png"
                        alt=""
                    />
                </div>
                <div class="flex flex-1 flex-col items-center lg:items-start">
                    <h1 class="text-3xl text-bookmark-blue">Bookmark in one click</h1>
                    <p class="text-bookmark-grey my-4 text-center sm:w-3/4 lg:text-left lg:w-full">
                        Organize your bookmarks however you like. Our simple drag-and-drop interface
                        gives you complete control over how you manage your favourite sites.
                    </p>
                    <button type="button" class="btn btn-purple">More info</button>
                </div>
            </div>
            <div
                class="
                    hidden
                    overflow-hidden
                    bg-bookmark-purple
                    rounded-r-full
                    absolute
                    h-80
                    w-2/4
                    -bottom-24
                    -left-36
                    lg:block
                "
            ></div>
        </div>
        <div class="relative mt-20 lg:mt-52">
            <div
                class="
                    container
                    flex flex-col
                    items-center
                    justify-center
                    gap-x-24
                    lg:flex-row-reverse
                "
            >
                <div class="flex flex-1 justify-center z-10 mb-10 lg:mb-0">
                    <img
                        class="w-5/6 h-5/6 sm:w-3/4 sm:h-3/4 md:w-full md:h-full"
                        src="./assets/img/illustration-features-tab-2.png"
                        alt=""
                    />
                </div>
                <div class="flex flex-1 flex-col items-center lg:items-start">
                    <h1 class="text-3xl text-bookmark-blue">Intelligent search</h1>
                    <p class="text-bookmark-grey my-4 text-center lg:text-left sm:w-3/4 lg:w-full">
                        Our powerful search feature will help you find saved sites in no time at
                        all. No need to crawl through all of your bookmarks.
                    </p>
                    <button type="button" class="btn btn-purple">More info</button>
                </div>
            </div>
            <div
                class="
                    hidden
                    overflow-hidden
                    bg-bookmark-purple
                    rounded-l-full
                    absolute
                    h-80
                    w-2/4
                    -bottom-24
                    -right-36
                    lg:block
                "
            ></div>
        </div>
        <div class="relative mt-20 lg:mt-24">
            <div class="container flex flex-col items-center justify-center gap-x-24 lg:flex-row">
                <div class="flex flex-1 justify-center z-10 mb-10 lg:mb-0">
                    <img
                        class="w-5/6 h-5/6 sm:w-3/4 sm:h-3/4 md:w-full md:h-full"
                        src="./assets/img/illustration-features-tab-3.png"
                        alt=""
                    />
                </div>
                <div class="flex flex-1 flex-col items-center lg:items-start">
                    <h1 class="text-3xl text-bookmark-blue">Share your bookmarks</h1>
                    <p class="text-bookmark-grey my-4 text-center sm:w-3/4 lg:w-full lg:text-left">
                        Easily share your bookmarks and collections with others. Create a shareable
                        link that you can send at the click of a button.
                    </p>
                    <button type="button" class="btn btn-purple">More info</button>
                </div>
            </div>
            <div
                class="
                    hidden
                    overflow-hidden
                    bg-bookmark-purple
                    rounded-r-full
                    absolute
                    h-80
                    w-2/4
                    -bottom-24
                    -left-36
                    lg:block
                "
            ></div>
        </div>
    </section>

    <section class="py-20 mt-20">
        <div class="mx-auto px-2 sm:w-3/4 lg:w-5/12">
            <h1 class="text-3xl text-center text-bookmark-blue">Download the extension</h1>
            <p class="text-center text-bookmark-grey mt-4">
                We've got more browsers in the pipeline. Please do let us know if you've got a
                favourite you'd like us to prioritize.
            </p>
        </div>
        <div
            class="
                container
                grid grid-cols-1
                gap-16
                max-w-screen-lg
                mt-16
                md:grid-cols-2
                lg:grid-cols-3
            "
        >
            <div class="flex flex-col rounded-md shadow-md lg:mb-16">
                <div class="p-6 flex flex-col items-center">
                    <img src="./assets/img/logo-chrome.svg" alt="Chrome" />
                    <h3 class="mt-5 mb-2 text-bookmark-blue text-lg">Add to Chrome</h3>
                    <p class="mb-2 text-bookmark-grey font-light">Minimum version 62</p>
                </div>
                <hr class="border-b border-bookmark-white" />
                <div class="flex p-6">
                    <button type="button" class="btn btn-purple flex-1">
                        Add & install extension
                    </button>
                </div>
            </div>
            <div class="flex flex-col rounded-md shadow-md lg:my-8">
                <div class="p-6 flex flex-col items-center">
                    <img src="./assets/img/logo-firefox.svg" alt="Firefox" />
                    <h3 class="mt-5 mb-2 text-bookmark-blue text-lg">Add to Firefox</h3>
                    <p class="mb-2 text-bookmark-grey font-light">Minimum version 62</p>
                </div>
                <hr class="border-b border-bookmark-white" />
                <div class="flex p-6">
                    <button type="button" class="btn btn-purple flex-1">
                        Add & install extension
                    </button>
                </div>
            </div>
            <div class="flex flex-col rounded-md shadow-md lg:mt-16">
                <div class="p-6 flex flex-col items-center">
                    <img src="./assets/img/logo-opera.svg" alt="Opera" />
                    <h3 class="mt-5 mb-2 text-bookmark-blue text-lg">Add to Opera</h3>
                    <p class="mb-2 text-bookmark-grey font-light">Minimum version 62</p>
                </div>
                <hr class="border-b border-bookmark-white" />
                <div class="flex p-6">
                    <button type="button" class="btn btn-purple flex-1">
                        Add & install extension
                    </button>
                </div>
            </div>
        </div>
    </section>

    <section id="faq" class="bg-bookmark-white py-20">
        <div class="mx-auto px-2 sm:w-3/4 lg:w-5/12">
            <h1 class="text-3xl text-center text-bookmark-blue">Frequently Asked Questions</h1>
            <p class="text-center text-bookmark-grey mt-4">
                Here are some of our FAQs. If you have any other questions you'd like answered
                please feel free to email us.
            </p>
        </div>
        <div class="flex flex-col mt-12 mx-auto px-4 sm:w-3/4 lg:w-5/12">
            <details class="group" open>
                <summary class="flex items-center border-b py-4 cursor-pointer">
                    <span class="flex-1">What is a Bookmark?</span>
                    <svg
                        class="
                            text-bookmark-purple
                            transition
                            duration-[250ms]
                            group-open:-rotate-180
                        "
                        xmlns="http://www.w3.org/2000/svg"
                        width="18"
                        height="12"
                    >
                        <path fill="none" stroke="#5267DF" stroke-width="3" d="M1 1l8 8 8-8" />
                    </svg>
                </summary>
                <div class="p-5 bg-white">
                    <p class="text-bookmark-grey">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur fugit
                        corporis voluptate fuga ad. Possimus ut inventore voluptatum ratione
                        repellendus a minus esse praesentium recusandae quasi dolore, ipsum,
                        accusantium aliquid.
                    </p>
                </div>
            </details>
            <details class="group">
                <summary class="flex items-center border-b py-4 cursor-pointer">
                    <span class="flex-1">How can I request a new browser?</span>
                    <svg
                        class="
                            text-bookmark-purple
                            transition
                            duration-[250ms]
                            group-open:-rotate-180
                        "
                        xmlns="http://www.w3.org/2000/svg"
                        width="18"
                        height="12"
                    >
                        <path fill="none" stroke="#5267DF" stroke-width="3" d="M1 1l8 8 8-8" />
                    </svg>
                </summary>
                <div class="p-5 bg-white">
                    <p class="text-bookmark-grey">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur fugit
                        corporis voluptate fuga ad. Possimus ut inventore voluptatum ratione
                        repellendus a minus esse praesentium recusandae quasi dolore, ipsum,
                        accusantium aliquid.
                    </p>
                </div>
            </details>
            <details class="group">
                <summary class="flex items-center border-b py-4 cursor-pointer">
                    <span class="flex-1">Is there a mobile app?</span>
                    <svg
                        class="
                            text-bookmark-purple
                            transition
                            duration-[250ms]
                            group-open:-rotate-180
                        "
                        xmlns="http://www.w3.org/2000/svg"
                        width="18"
                        height="12"
                    >
                        <path fill="none" stroke="#5267DF" stroke-width="3" d="M1 1l8 8 8-8" />
                    </svg>
                </summary>
                <div class="p-5 bg-white">
                    <p class="text-bookmark-grey">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur fugit
                        corporis voluptate fuga ad. Possimus ut inventore voluptatum ratione
                        repellendus a minus esse praesentium recusandae quasi dolore, ipsum,
                        accusantium aliquid.
                    </p>
                </div>
            </details>
            <details class="group">
                <summary class="flex items-center border-b py-4 cursor-pointer">
                    <span class="flex-1">What about other Chromium browsers?</span>
                    <svg
                        class="
                            text-bookmark-purple
                            transition
                            duration-[250ms]
                            group-open:-rotate-180
                        "
                        xmlns="http://www.w3.org/2000/svg"
                        width="18"
                        height="12"
                    >
                        <path fill="none" stroke="#5267DF" stroke-width="3" d="M1 1l8 8 8-8" />
                    </svg>
                </summary>
                <div class="p-5 bg-white">
                    <p class="text-bookmark-grey">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur fugit
                        corporis voluptate fuga ad. Possimus ut inventore voluptatum ratione
                        repellendus a minus esse praesentium recusandae quasi dolore, ipsum,
                        accusantium aliquid.
                    </p>
                </div>
            </details>
            <button type="button" class="btn btn-purple mt-12 flex self-center">More Info</button>
        </div>
    </section>

    <section id="contact" class="bg-bookmark-purple text-white py-20">
        <div class="container">
            <div class="mx-auto sm:w-3/4 lg:w-2/4">
                <p class="font-light uppercase text-center mb-8">35,000+ ALREADY JOINED</p>
                <h1 class="text-3xl text-center">Stay up-to-date with what we're doing</h1>
                <div class="flex flex-col gap-6 mt-8 sm:flex-row">
                    <input
                        type="e-mail"
                        v-model="email"
                        placeholder="Enter your e-mail address"
                        class="flex-1 px-3 py-3 rounded-md text-black focus:outline-none"
                    />
                    <button
                        type="button"
                        class="
                            btn
                            bg-bookmark-red
                            focus:bg-bookmark-white focus:text-black
                            hover:bg-bookmark-white hover:text-black
                            disabled:opacity-70
                        "
                        :disabled="isButtonDisabled"
                    >
                        Contact Us
                    </button>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-bookmark-blue py-8">
        <div class="container flex flex-col md:flex-row items-center">
            <div class="flex flex-1 flex-wrap items-center justify-center gap-12 md:justify-start">
                <img src="./assets/img/logo-bookmark-white.png" alt="" />
                <ul class="flex text-white uppercase gap-12 text-xs">
                    <li class="cursor-pointer">
                        <a
                            class="
                                transition
                                outline-none
                                hover:text-bookmark-red
                                focus:text-bookmark-red
                            "
                            href="#features"
                            >Features</a
                        >
                    </li>
                    <li class="cursor-pointer">
                        <a
                            class="
                                transition
                                outline-none
                                hover:text-bookmark-red
                                focus:text-bookmark-red
                            "
                            href="#faq"
                            >FAQ</a
                        >
                    </li>
                    <li class="cursor-pointer">
                        <a
                            class="
                                transition
                                outline-none
                                hover:text-bookmark-red
                                focus:text-bookmark-red
                            "
                            href="#contact"
                            >Contact</a
                        >
                    </li>
                </ul>
            </div>
            <div class="flex gap-10 mt-12 md:mt-0">
                <a href="#" class="transition outline-none group">
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        aria-hidden="true"
                        focusable="false"
                        class="
                            text-white
                            w-6
                            h-6
                            transition
                            group-hover:text-bookmark-red
                            group-focus:text-bookmark-red
                        "
                        role="img"
                        viewBox="0 0 512 512"
                    >
                        <path
                            fill="currentColor"
                            d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z"
                        />
                    </svg>
                </a>
                <a href="#" class="transition outline-none group">
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        aria-hidden="true"
                        focusable="false"
                        class="
                            text-white
                            w-6
                            h-6
                            transition
                            group-hover:text-bookmark-red
                            group-focus:text-bookmark-red
                        "
                        role="img"
                        viewBox="0 0 448 512"
                    >
                        <path
                            fill="currentColor"
                            d="M400 32H48A48 48 0 0 0 0 80v352a48 48 0 0 0 48 48h137.25V327.69h-63V256h63v-54.64c0-62.15 37-96.48 93.67-96.48 27.14 0 55.52 4.84 55.52 4.84v61h-31.27c-30.81 0-40.42 19.12-40.42 38.73V256h68.78l-11 71.69h-57.78V480H400a48 48 0 0 0 48-48V80a48 48 0 0 0-48-48z"
                        />
                    </svg>
                </a>
            </div>
        </div>
    </footer>
</template>

<script>
import { ref, watch } from 'vue'

export default {
    setup() {
        const email = ref('')
        const isEmailValid = ref(false)
        const isButtonDisabled = ref(false)
        const emailRegEx =
            /^(([^<>()\[\]\\.,;:\s@"]+(\.[^<>()\[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/

        watch(email, (email) => {
            isButtonDisabled.value = true
            if (emailRegEx.test(email)) {
                isEmailValid.value = true
                isButtonDisabled.value = false
            }
        })

        return { email, isButtonDisabled }
    },
}
</script>

<style></style>
