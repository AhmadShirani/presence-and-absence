<template>
    <div class="p-5 w-screen h-screen flex flex-col gap-7 items-center justify-center">


        <div class="relative overflow-x-auto">
    <table class="w-full text-sm text-left rtl:text-right text-gray-500 dark:text-gray-400">
        <thead class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
            <tr>
                <th scope="col" class="px-6 py-3">
                   نام و نام خانوادگی
                </th>
                <th scope="col" class="px-6 py-3">
                    ثبت زمان ورود
                </th>
                <th scope="col" class="px-6 py-3">
                    ثبت زمان خروج
                </th>
                <th scope="col" class="px-6 py-3">
                    ساعات حضور
                </th>
            </tr>
        </thead>
        <tbody>
            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 border-gray-200">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                   احمد شیرانی
                </th>
                <td class="px-6 py-4">
                   <NuxtLink to="/time-login">زمان ورود</NuxtLink>
                </td>
                <td class="px-6 py-4">
                   <NuxtLink to="/departure-time">زمان خروج</NuxtLink>
                </td>
                <td class="px-6 py-4">
                    
                </td>
            </tr>
            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 border-gray-200">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    ستایش جعفری
                </th>
                <td class="px-6 py-4">
                   <NuxtLink to="/time-login.vue">زمان ورود</NuxtLink>
                </td>
                <td class="px-6 py-4">
                   <NuxtLink to="/departure-time">زمان خروج</NuxtLink>
                </td>
                <td class="px-6 py-4">
                    
                </td>
            </tr>
            <tr class="bg-white dark:bg-gray-800">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    محمد رضا زرگرزاده
                </th>
                <td class="px-6 py-4">
                   <NuxtLink to="/time-login">زمان ورود</NuxtLink>
                </td>
                <td class="px-6 py-4">
                   <NuxtLink to="/departure-time">زمان خروج</NuxtLink>
                </td>
                <td class="px-6 py-4">
                    
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