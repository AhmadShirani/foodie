<template>
    <div class="w-screen h-screen flex items-center justify-center flex-col gap-5 p-10">
        <h1 class="ml-72">فراموشی رمز عبور</h1>
        <p>لطفا حهت دریافت رمز جدید یکی از گزینه های زیر را انتخاب کنید</p>
        <div class="border border-gray-400 p-5 w-full">
            <h2 class="mb-3">ایمیل</h2>
            <p>برای بازیابی رمز عبور خود ایمیل خود را وارد کنید.</p>
        </div>
        <div class="w-full border border-gray-400 p-5">
            <h2 class="mb-3">شماره همراه</h2>
            <p>برای بازیابی رمز عبور خود شماره همراه خود را وارد کنید.</p>
        </div>
        <NuxtLink class="bg-[#307a59] text-white text-center p-3 rounded mt-3 px-48" to="/">ادامه</NuxtLink>
    </div>
</template>
<style scoped>
*
{
  direction: rtl;
}
</style>