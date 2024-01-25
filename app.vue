<template>
  <div class="flex flex-col justify-center items-center h-screen w-screen bg-[#DBE8EE]">
    <div class="flex h-96 w-96 flex-col items-center justify-center gap-4 rounded-lg bg-white">
      <div class="flex h-6 w-56 justify-center text-lg font-semibold text-purple-600">
        <p>SIGN UP</p>
      </div>
      <div class="flex">
        <input id="txt_name" placeholder="Name" class="h-12 w-72 rounded-3xl border px-4 text-left" />
      </div>
      <div class="">
        <input id="txt_email" placeholder="Email" class="h-12 w-72 rounded-3xl border px-4 text-left" />
      </div>
      <div class="">
        <input type="button" value="SIGN UP"
          class="h-12 w-72 rounded-3xl border bg-[#8D6CC7] px-4 text-center text-sm font-semibold text-white" />
      </div>
      <div class="flex">
        <p class="w-full border-b-2"></p>
        <p class="text-nowrap text-sm font-semibold text-gray-400">OR SIGN UP WITH</p>
        <p class="w-full border-b-2"></p>
      </div>
      <div class="w-100 flex justify-around gap-10">
        <input class="h-full w-full rounded-full bg-[#EB5959] px-4 py-2" type="button" value="G" />
        <input class="h-full w-full rounded-full bg-[#527ED5] px-4 py-2" type="button" value="F" />
        <input class="h-full w-full rounded-full bg-[#62BDEC] px-4 py-2" type="button" value="T" />
      </div>
    </div>
    <p class="text-gray-500 font-medium text-sm py-2">ALREADY HAVE AN ACCOUNT?<span
        class="text-[#8D6CC7] font-bold text-sm px-1">LOG IN</span></p>
  </div>
</template>