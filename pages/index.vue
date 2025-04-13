<template>
    <div class="p-5 w-screen h-screen flex flex-col gap-7 items-center justify-center bg-[#7462e1]">


        <div class="relative overflow-x-auto rounded-md">
    <table class="w-full text-sm text-left rtl:text-right text-gray-500 dark:text-gray-400 rounded shadow-xl/20">
        <thead class=" text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
            <tr>
                <th scope="col" class="px-6 py-3 text-center">
                   نام و نام خانوادگی
                </th>
                <th scope="col" class="px-6 py-3 text-center">
                    وضعیت
                </th>
                <th scope="col" class="px-6 py-3 text-center">
                    ساعات حضور
                </th>
                <th scope="col" class="px-6 py-3 text-center">
                    عملیات
                </th>
            </tr>
        </thead>
        <tbody>
            <tr class="bg-white">
                <th id="name1" scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white text-center">
                   احمد شیرانی
                </th>
                <td class="px-6 py-4 text-center">
                    
                </td>
                <td class="px-6 py-4 text-center">
                   
                </td>
                    <NuxtLink class="" to="/time-login">
                        <td class="text-white bg-[#7462e1] flex justify-center items-center w-24 h-14 border-1 border-dotted">ثبت زمان</td>
                   </NuxtLink>
            </tr>
            <tr class="bg-white">
                <th id="name-2" scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white text-center">
                    ستایش جعفری
                </th>
                <td class="px-6 py-4 text-center">
                    
                </td>
                <td class="px-6 py-4 text-center">
                   
                </td>
                <NuxtLink class="" to="/time-login">
                        <td class="text-white bg-[#7462e1] flex justify-center items-center w-24 h-14">ثبت زمان</td>
                   </NuxtLink>
            </tr>
            <tr class="bg-white dark:bg-gray-800 dark:border-gray-700 border-gray-200">
                <th id="name-3" scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    محمدرضا زرگرزاده
                </th>
                <td class="px-6 py-4 text-center">
                   
                </td>
                <td class="px-6 py-4 text-center">
                   
                </td>
                <NuxtLink class="" to="/time-login">
                        <td class="text-white bg-[#7462e1] flex justify-center items-center w-24 h-14">ثبت زمان</td>
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