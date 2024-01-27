<template>
    <div class="flex flex-col justify-center items-center h-screen w-screen bg-[#DBE8EE]">
        <div
            class="flex h-full w-full sm:w-96 sm:h-96 md:h-96 md:w-96 lg:w-96 lg:h-96  flex-col items-center justify-center gap-4 rounded-lg bg-white">
            <div class="flex h-6 w-56 justify-center text-lg font-semibold text-purple-600">
                <p>SIGN UP</p>
            </div>
            <div>
                <input id="txt_name" placeholder="Email" required class="h-12 w-72 rounded-3xl border px-4 text-left" />
            </div>
            <div>
                <input id="txt_email" placeholder="Password" required type="password"
                    class="h-12 w-72 rounded-3xl border px-4 text-left" />
            </div>
            <div>
                <input type="button" value="SIGN UP"
                    class="h-12 w-72 rounded-3xl border bg-[#8D6CC7] px-4 text-center text-sm font-semibold text-white cursor-pointer active:bg-[#a79fb9]" />
            </div>
            <div class="flex flex-row">
                <p class="text-nowrap text-sm font-semibold text-gray-400">OR SIGN UP WITH</p>
            </div>
            <div class="flex justify-around gap-4">
                <button class="h-full w-full rounded-full bg-[#EB5959] p-2 active:bg-[#a79fb9]">
                    <svg class="w-6 h-6 text-sm text-gray-800 dark:text-white" aria-hidden="true"
                        xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
                        <path fill-rule="evenodd"
                            d="M12 22a10 10 0 0 1-7.1-3A9.9 9.9 0 0 1 5 4.8C7 3 9.5 2 12.2 2h.2c2.4 0 4.8 1 6.6 2.6l-2.5 2.3a6.2 6.2 0 0 0-4.2-1.6c-1.8 0-3.5.7-4.8 2a6.6 6.6 0 0 0-.1 9.3c1.2 1.3 2.9 2 4.7 2h.1a6 6 0 0 0 4-1.1c1-.9 1.8-2 2.1-3.4v-.2h-6v-3.4h9.6l.1 1.9c-.1 5.7-4 9.6-9.7 9.6H12Z"
                            clip-rule="evenodd"></path>
                    </svg>
                </button>
                <button class="h-full w-full rounded-full bg-[#527ED5] p-2 active:bg-[#a79fb9]">
                    <svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg"
                        fill="currentColor" viewBox="0 0 24 24">
                        <path fill-rule="evenodd"
                            d="M13.1 6H15V3h-1.9A4.1 4.1 0 0 0 9 7.1V9H7v3h2v10h3V12h2l.6-3H12V6.6a.6.6 0 0 1 .6-.6h.5Z"
                            clip-rule="evenodd" />
                    </svg>
                </button>
                <button class="h-full w-full rounded-full bg-[#60BDEF] p-2 active:bg-[#a79fb9]">
                    <svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg"
                        fill="currentColor" viewBox="0 0 24 24">
                        <path fill-rule="evenodd"
                            d="M22 5.9c-.7.3-1.5.5-2.4.6a4 4 0 0 0 1.8-2.2c-.8.5-1.6.8-2.6 1a4.1 4.1 0 0 0-6.7 1.2 4 4 0 0 0-.2 2.5 11.7 11.7 0 0 1-8.5-4.3 4 4 0 0 0 1.3 5.4c-.7 0-1.3-.2-1.9-.5a4 4 0 0 0 3.3 4 4.2 4.2 0 0 1-1.9.1 4.1 4.1 0 0 0 3.9 2.8c-1.8 1.3-4 2-6.1 1.7a11.7 11.7 0 0 0 10.7 1A11.5 11.5 0 0 0 20 8.5V8a10 10 0 0 0 2-2.1Z"
                            clip-rule="evenodd" />
                    </svg>
                </button>
            </div>
        </div>
        <p class="text-gray-500 font-medium text-sm py-2">ALREADY HAVE AN ACCOUNT?<span
                class="text-[#8D6CC7] font-bold text-sm px-1 cursor-pointer active:text-[#a79fb9]">LOG IN</span></p>
    </div>
</template>
<script setup>
definePageMeta({
    page: "login"
})
</script>
<style></style>