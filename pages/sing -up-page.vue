<template>
    <div class="w-screen h-screen flex items-center justify-center flex-col gap-5 p-10">
        <div class="flex flex-col gap-2 ml-48">
            <h1>خوش آمدید</h1>
            <p>لطفا اطلاعات زیر را کامل کنید</p>
        </div>
        <div class="flex flex-col gap-5 p-5 w-full">
            <label for="username">نام کاربری</label>
            <input class="border border-gray-400 h-10 p-5" type="text">
            <label for="username">ایمیل</label>
            <input class="border border-gray-400 h-10 p-5" type="email">
            <label for="username">رمز عبور</label>
            <input class="border border-gray-400 h-10 p-5" type="password">
            <NuxtLink to="">فراموشی رمز عبور</NuxtLink>
            <NuxtLink class="bg-[#307a59] text-white text-center p-3 rounded mt-3" to="">ورود</NuxtLink>
        </div>
    </div>
</template>

<style scoped>
*
{
  direction: rtl;
}
</style>