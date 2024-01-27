<template>
    <div class="bg-[#31315B] w-screen h-screen flex-col justify-center px-8 py-8">
        <div class="w-80 h-14 rounded-full bg-[#282851] flex flex-row justify-between items-center px-3 py-1">
            <button class="px-6 text-nowrap font-semibold text-white">Add Task</button>
            <button class="rounded-full bg-white w-10 h-10">
            </button>
        </div>

    </div>
</template>
<script setup>
definePageMeta({
    page: "main"
})
</script>
<style scoped>
.w-100 {
    width: 50rem;
}
</style>