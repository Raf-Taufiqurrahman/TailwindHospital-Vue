<template>
    <nav class="w-full flex flex-row p-5 border-b fixed bg-white items-center">
        <div class="flex items-center gap-2">
            <i class="fas fa-heartbeat text-[30px] text-teal-500"></i>
            <h1 class="font-bold text-2xl text-gray-700">WeCare</h1>
        </div>
        <div class="ml-auto">
            <ul class="hidden md:flex flex-row gap-4">
                <li class="text-gray-500 font-semibold">
                    <a href="">Home</a>
                </li>
                <li class="text-gray-500 font-semibold">
                    <a href="">Services</a>
                </li>
                <li class="text-gray-500 font-semibold">
                    <a href="">About</a>
                </li>
                <li class="text-gray-500 font-semibold">
                    <a href="">Doctors</a>
                </li>
                <li class="text-gray-500 font-semibold">
                    <a href="">Book</a>
                </li>
                <li class="text-gray-500 font-semibold">
                    <a href="">Review</a>
                </li>
            </ul>
        </div>
    </nav>
</template>

<script>
export default {
    setup() {
    }
}
</script>