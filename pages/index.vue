<template>
    <div class="p-5 w-screen h-screen flex flex-col gap-7 items-center justify-center">


        <div class="relative overflow-x-auto">
    <table class="w-full text-sm text-left rtl:text-right text-gray-500 dark:text-gray-400 border">
        <thead class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400 border">
            <tr>
                <th scope="col" class="px-6 py-3 border">
                   نام و نام خانوادگی
                </th>
                <th scope="col" class="px-6 py-3 border">
                    ثبت زمان ورود
                </th>
                <th scope="col" class="px-6 py-3 border">
                    ساعات حضور
                </th>
            </tr>
        </thead>
        <tbody>
            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 border-gray-200">
                <th scope="row" class="border px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white text-center">
                   احمد شیرانی
                </th>
                <!-- <td class="px-6 py-4 border text-[#02312c] bg-[#00ff95] text-center"> -->
                   <NuxtLink class="block" to="/time-login">
                    <td class="px-10 py-4 border text-[#02312c] bg-[#00ff95] text-center w-full h-full">زمان ورود</td>
                   </NuxtLink>
                <!-- </td> -->
                <NuxtLink class="block" to="/departure-time">
                    <td class="px-10 py-4 border bg-[#df0000] text-white text-center">زمان خروج</td>
                   </NuxtLink>
                <td class="px-6 py-4 border text-center">
                    
                </td>
            </tr>
            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 border-gray-200 border">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white border">
                    ستایش جعفری
                </th>
                <NuxtLink class="block" to="/time-login">
                    <td class="px-10 py-4 border text-[#02312c] bg-[#00ff95] text-center w-full h-full">زمان ورود</td>
                   </NuxtLink>
                   <NuxtLink class="block" to="/departure-time">
                    <td class="px-10 py-4 border bg-[#df0000] text-white text-center">زمان خروج</td>
                   </NuxtLink>
                <td class="px-6 py-4 border text-center">
                    
                </td>
            </tr>
            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 border-gray-200 border">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white border">
                    محمدرضا زرگرزاده
                </th>
                <NuxtLink class="block" to="/time-login">
                    <td class="px-10 py-4 border text-[#02312c] bg-[#00ff95] text-center w-full h-full">زمان ورود</td>
                   </NuxtLink>
                   <NuxtLink class="block" to="/departure-time">
                    <td class="px-10 py-4 border bg-[#df0000] text-white text-center">زمان خروج</td>
                   </NuxtLink>
                <td class="px-6 py-4 border text-center">
                   
                </td>
            </tr>
        </tbody>
    </table>
</div>

    </div>
</template>
<style>
*
{
    direction: rtl;
}
</style>