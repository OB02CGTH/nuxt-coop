<template>
  <section>
    <div class="mx-auto max-w-screen-2xl px-4 lg:px-12 p-6">
      <!-- Start coding here -->
      <div
        class="block p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700"
      >
        <h5 class="text-3xl font-bold text-gray-900 dark:text-white ml-2">
          ฟอร์มขอกู้ฉุกเฉิน
        </h5>
        <hr class="my-5" />
        <form>
          <div class="grid grid-cols-2 gap-2">
            <div class="mb-6">
              <label for="email" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">จำนวนการกู้</label>
              <input type="email" id="email" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="0.00" required>
            </div>
            <div class="mb-6">
              <label for="password" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">เหตุผลการกู้</label>
              <input type="y" id="password" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" required>
            </div>
            <div>
              <label class="block mb-2 text-sm font-medium text-gray-900 dark:text-white" for="file_input">ไฟเอกสารหนึ่ง</label>
              <input class="block w-full text-sm text-gray-900 border border-gray-300 rounded-lg cursor-pointer bg-gray-50 dark:text-gray-400 focus:outline-none dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400" id="file_input" type="file">
            </div>
            <div>
              <label class="block mb-2 text-sm font-medium text-gray-900 dark:text-white" for="file_input">ไฟเอกสารสอง</label>
              <input class="block w-full text-sm text-gray-900 border border-gray-300 rounded-lg cursor-pointer bg-gray-50 dark:text-gray-400 focus:outline-none dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400" id="file_input" type="file">
            </div>
            <div>
              <label class="block mb-2 text-sm font-medium text-gray-900 dark:text-white" for="file_input">ไฟเอกสารสาม</label>
              <input class="block w-full text-sm text-gray-900 border border-gray-300 rounded-lg cursor-pointer bg-gray-50 dark:text-gray-400 focus:outline-none dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400" id="file_input" type="file">
            </div>
            <div>
              <label class="block mb-2 text-sm font-medium text-gray-900 dark:text-white" for="file_input">ไฟเอกสารสี่</label>
              <input class="block w-full text-sm text-gray-900 border border-gray-300 rounded-lg cursor-pointer bg-gray-50 dark:text-gray-400 focus:outline-none dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400" id="file_input" type="file">
            </div>
          </div>
          <NuxtLink to="/confirmborrow">
            <button type="submit" class="text-white mt-5 bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm w-full sm:w-auto px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">ยื่นคำขอกู้</button>
          </NuxtLink>
        </form>
      </div>
    </div>
  </section>
</template>