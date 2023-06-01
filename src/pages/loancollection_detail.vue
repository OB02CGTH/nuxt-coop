<template>
  <section class="p-3 sm:p-5">
    <div class="mx-auto max-w-screen-lg px-4 lg:px-12 p-6">
      <!-- Start coding here -->
      <div class="block p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
        <h5 class="text-3xl font-bold text-gray-900 dark:text-white ml-2">
          รายละเอียดการค้างชำระหนี้
        </h5>
        <hr class="my-5" />
        <div>
          <h2 class="mb-2 text-2xl font-semibold text-gray-900 dark:text-white">ข้อมูลผู้ขอกู้:</h2>
          <div class="grid grid-cols-3 gap-y-5 mb-5">
            <div>
              ชื่อ: นาย xxx xxx
            </div>
            <div>
              รหัสสมาชิก: xxxxxx
            </div>
            <div>
              รวมเป็นเงินค้างชำระ: xxxxxx
            </div>
            <div>
              ไม่สามารถส่งเงินชำระหนี้ได้: x ครั้ง
            </div>
            <div>
              ตั้งแต่งวดที่: xx
            </div>
            <div>
              ถึงงวดที่: x
            </div>
          </div>
          <h2 class="mb-2 text-lg font-semibold text-gray-900 dark:text-white">รายการงวดที่ยังไม่ชำระ:</h2>
          <div class="relative overflow-x-auto mb-5">
            <table class="w-full text-sm text-left text-gray-500 dark:text-gray-400">
              <thead class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
                <tr>
                  <th scope="col" class="px-6 py-3">
                  </th>
                  <th scope="col" class="px-6 py-3">
                    งวดที่
                  </th>
                  <th scope="col" class="px-6 py-3">
                    ประจำวันที่
                  </th>
                  <th scope="col" class="px-6 py-3">
                    เป็นจำนวนเงิน/บาท
                  </th>
                </tr>
              </thead>
              <tbody>
                <tr v-for="i in 3" class="bg-white border-b dark:bg-gray-800 dark:border-gray-700">
                  <th scope="row" class="w-1 px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    {{ i }}
                  </th>
                  <td class="px-6 py-4">
                    xx
                  </td>
                  <td class="px-6 py-4">
                    xx/xx/xxx
                  </td>
                  <td class="px-6 py-4">
                    x,xxx
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
          <h2 class="mb-2 text-lg font-semibold text-gray-900 dark:text-white"> ขั้นตอนการดำเนินการ:</h2>
          <ul class="space-y-4 text-gray-500 list-disc list-inside dark:text-gray-400">
            <li>
              List item one
              <ol class="pl-5 mt-2 space-y-1 list-decimal list-inside">
                <li>You might feel like you are being really "organized" o</li>
                <li>Nested navigation in UIs is a bad idea too, keep things as flat as possible.</li>
                <li>Nesting tons of folders in your source code is also not helpful.</li>
              </ol>
            </li>
            <li>
              List item two
              <ul class="pl-5 mt-2 space-y-1 list-decimal list-inside">
                <li>I'm not sure if we'll bother styling more than two levels deep.</li>
                <li>Two is already too much, three is guaranteed to be a bad idea.</li>
                <li>If you nest four levels deep you belong in prison.</li>
              </ul>
            </li>
            <li>
              List item three
              <ul class="pl-5 mt-2 space-y-1 list-decimal list-inside">
                <li>Again please don't nest lists if you want</li>
                <li>Nobody wants to look at this.</li>
                <li>I'm upset that we even have to bother styling this.</li>
              </ul>
            </li>
          </ul>
          <h2 class="mb-2 text-lg font-semibold text-gray-900 dark:text-white">Password requirements:</h2>
          <ul class="max-w-md space-y-1 text-gray-500 list-inside dark:text-gray-400">
            <li class="flex items-center">
              <svg class="w-4 h-4 mr-1.5 text-green-500 dark:text-green-400 flex-shrink-0" fill="currentColor"
                viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd"
                  d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                  clip-rule="evenodd"></path>
              </svg>
              At least 10 characters
            </li>
            <li class="flex items-center">
              <svg class="w-4 h-4 mr-1.5 text-green-500 dark:text-green-400 flex-shrink-0" fill="currentColor"
                viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd"
                  d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                  clip-rule="evenodd"></path>
              </svg>
              At least one lowercase character
            </li>
            <li class="flex items-center">
              <svg class="w-4 h-4 mr-1.5 text-gray-400 flex-shrink-0" fill="currentColor" viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd"
                  d="M10 18a8 8 0 100-16 8 8 0 000 16zM8.707 7.293a1 1 0 00-1.414 1.414L8.586 10l-1.293 1.293a1 1 0 101.414 1.414L10 11.414l1.293 1.293a1 1 0 001.414-1.414L11.414 10l1.293-1.293a1 1 0 00-1.414-1.414L10 8.586 8.707 7.293z"
                  clip-rule="evenodd"></path>
              </svg>
              At least one special character, e.g., ! @ # ?
            </li>
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
function randomnumber() {
  return Math.floor(Math.random() * 3) + 1;
}
function randomnumber2() {
  return Math.floor(Math.random() * 12) + 1;
}
</script>
