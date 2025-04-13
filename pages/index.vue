<template>
    <div class="p-5 w-screen h-screen flex flex-col gap-7 items-center justify-center">


        <div class="relative overflow-x-auto">
    <table class="w-full text-sm text-left rtl:text-right text-gray-500 dark:text-gray-400 border">
        <thead class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400 border">
            <tr>
                <th scope="col" class="px-6 py-3 border text-center">
                   نام و نام خانوادگی
                </th>
                <th scope="col" class="px-6 py-3 border text-center">
                    وضعیت
                </th>
                <th scope="col" class="px-6 py-3 border text-center">
                    ساعات حضور
                </th>
                <th scope="col" class="px-6 py-3 border text-center">
                    عملیات
                </th>
            </tr>
        </thead>
        <tbody>
            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 border-gray-200">
                <th scope="row" class="border px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white text-center">
                   احمد شیرانی
                </th>
                   <!-- <NuxtLink class="block" to="/time-login">
                    <td class="px-10 py-4 border text-[#02312c] bg-[#00ff95] text-center w-full h-full">زمان ورود</td>
                   </NuxtLink>
                <NuxtLink class="block" to="/departure-time">
                    <td class="px-10 py-4 border bg-[#df0000] text-white text-center">زمان خروج</td>
                   </NuxtLink> -->
                <td class="px-6 py-4 border text-center">
                    
                </td>
                <td class="px-6 py-4 border text-center">
                   
                </td>
                    <NuxtLink class="" to="/time-login">
                        <td class="border text-[#02312c] bg-[#00ff95] flex justify-center items-center w-24 h-14">ثبت زمان</td>
                   </NuxtLink>
            </tr>
            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 border-gray-200 border">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white border text-center">
                    ستایش جعفری
                </th>
                <td class="px-6 py-4 border text-center">
                    
                </td>
                <td class="px-6 py-4 border text-center">
                   
                </td>
                <NuxtLink class="" to="/time-login">
                        <td class="border text-[#02312c] bg-[#00ff95] flex justify-center items-center w-24 h-14">ثبت زمان</td>
                   </NuxtLink>
            </tr>
            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 border-gray-200 border">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white border">
                    محمدرضا زرگرزاده
                </th>
                <!-- <NuxtLink class="block" to="/time-login">
                    <td class="px-10 py-4 border text-[#02312c] bg-[#00ff95] text-center w-full h-full">زمان ورود</td>
                   </NuxtLink>
                   <NuxtLink class="block" to="/departure-time">
                    <td class="px-10 py-4 border bg-[#df0000] text-white text-center">زمان خروج</td>
                   </NuxtLink> -->
                <td class="px-6 py-4 border text-center">
                   
                </td>
                <td class="px-6 py-4 border text-center">
                   
                </td>
                <NuxtLink class="" to="/time-login">
                        <td class="border text-[#02312c] bg-[#00ff95] flex justify-center items-center w-24 h-14">ثبت زمان</td>
                   </NuxtLink>
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