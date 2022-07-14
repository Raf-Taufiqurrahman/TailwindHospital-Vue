<template>
    <section class="w-full py-16 px-4">
        <div class="container mx-auto">
            <div class="flex flex-row items-center text-center justify-center pb-10">
                <h3 class="text-teal-700 text-cta text-5xl font-bold uppercase">Book Now</h3>
            </div>
            <div class="flex flex-col md:flex-row gap-1.5 items-center justify-center">
                <img src="../assets/image/book-img.svg" class="w-full md:w-1/2 object-cover" />
                <div class="bg-white p-8 w-full rounded-lg box">
                    <h3 class="text-center text-gray-700 text-xl leading-relaxed tracking-wider font-semibold">
                        Book Appointment
                    </h3>
                    <div class="py-3">
                        <input type="text" placeholder="Your Name"
                            class="rounded w-full p-1.5 focus:ring-teal-500 focus:ring-2 focus:outline-none border-teal-500 border-2" />
                    </div>
                    <div class="py-3">
                        <input type="number" placeholder="Your Number"
                            class="rounded w-full p-1.5 focus:ring-teal-500 focus:ring-2 focus:outline-none border-teal-500 border-2" />
                    </div>
                    <div class="py-3">
                        <input type="email" placeholder="Your Email"
                            class="rounded w-full p-1.5 focus:ring-teal-500 focus:ring-2 focus:outline-none border-teal-500 border-2" />
                    </div>
                    <div class="py-3">
                        <input type="date" placeholder=""
                            class="rounded w-full p-1.5 focus:ring-teal-500 focus:ring-2 focus:outline-none border-teal-500 border-2" />
                    </div>
                    <div
                        class="flex items-center border-2 p-2 w-fit border-teal-500 btn hover:bg-teal-500 group transition duration-500 ease-in-out rounded-md mt-3">
                        <a href="#" class="leading-relaxed tracking-wider text-teal-500 group-hover:text-white">
                            Book Now
                        </a>
                        <svg xmlns="http://www.w3.org/2000/svg"
                            class="h-6 w-6 ml-2 text-teal-500 group-hover:text-white group-hover:rotate-90 transition duration-500 ease-in-out"
                            fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M13 9l3 3m0 0l-3 3m3-3H8m13 0a9 9 0 11-18 0 9 9 0 0118 0z" />
                        </svg>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>