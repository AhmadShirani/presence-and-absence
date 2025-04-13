<script>

</script>
<template>
    <div class="fixed">
        <div class="text-white w-screen h-screen flex flex-col gap-7 items-center justify-center bg-gray-100 ">
        <div class="bg-[#7462e1] rounded-b-full h-3/4 w-7xl absolute top-0"></div>
        <div class="z-10">
            <h1 class="flex items-center justify-center font-bold text-2xl mb-11">زمان ورود</h1>
        <button class="rounded-full bg-white w-40 h-40 mb-5 mr-20"><h2 class="justify-center text-black text-center text-4xl">ثبت</h2></button>
        <div class="bg-white w-80 h-80 rounded-3xl text-black flex justify-center items-center flex-col">
            <h2>تاریخ امروز</h2>
            <div class="bg-[#7462e1] rounded mt-6 text-white w-64 h-10 flex items-center justify-center">
                <p class="block text-center"></p>
            </div>
            <h2 class="mt-4">زمان</h2>
            <div class="bg-[#7462e1] rounded mt-5 text-white w-64 h-10 flex items-center justify-center mb-5">
                <p class="block text-center"></p>
            </div>
            <NuxtLink class="bg-[#7462e1] p-1 w-28 h-10 rounded mt-4 text-white text-center" to="/">خروج</NuxtLink> 
        </div>
        </div>
    </div>
    </div>
</template>