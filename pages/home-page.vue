<template>
    <div class="p-5 flex flex-col gap-4">
        <h1 class="font-bold flex justify-center">خانه</h1>
        <div class="bg-gray-400 p-2 rounded">11</div>
        <div>
            <img src="" alt="">
            <input type="search">
        </div>
        <div class="bg-[#307a59] p-5 rounded flex flex-col gap-3">
            <h2>لتلمملمیبنتملتبما</h2>
            <h2>ijflfjerrjflj</h2>
            <NuxtLink class="bg-white text-[#307a59] p-2 text-center w-20 rounded" to="">بزن بریم</NuxtLink>
        </div>
        <div class="bg-gray-300 p-5 grid grid-cols-2">
            <div class="grid">
            <h2 class="font-bold">غذاهای جدید</h2>
            <p>برای مشاهده به لینک زیر بروید</p>
            <NuxtLink class=" bg-[#307a59] text-white p-2 w-20 text-center rounded mt-5" to="">بزن بریم</NuxtLink>
            </div>
            <img class="w-36 mr-5 mt-2" src="/public/img/1.png" alt="">
        </div>
        <h2 class="mr-4 mt-3">برترین غذاها</h2>
        <div class="flex flex-row">
            <div class="grid grid-rows-2 p-5 w-52">
                <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-sm dark:bg-gray-800 dark:border-gray-700">
                    <a href="#">
                       <img class="rounded-t" src="/public/img/food.png" alt="">
                    </a>
                    <div class="p-5">
                        <a href="#">
                            <h5 class="mb-2 font-bold text-gray-900 dark:text-white">ماکارانی</h5>
                        </a>
                        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">20 هزار تومان</p>
                    </div>
                </div>
            </div>
            <div class="grid grid-rows-2 p-5 gap-2 w-52">
                <div class="bg-white border border-gray-200 rounded-lg shadow-sm dark:bg-gray-800 dark:border-gray-700">
                    <a href="#">
                       <img class="rounded-t" src="/public/img/food.png" alt="">
                    </a>
                    <div class="p-5">
                        <a href="#">
                            <h5 class="mb-2 font-bold text-gray-900 dark:text-white">ماکارانی</h5>
                        </a>
                        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">20 هزار تومان</p>
                    </div>
                </div>
            </div>
            
        </div>
    </div>
</template>
<style scoped>
*
{
  direction: rtl;
}
</style>