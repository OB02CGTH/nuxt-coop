<template>
  <section>
    <div class="mx-auto max-w-screen-2xl px-4 lg:px-12 p-6">
      <!-- Start coding here -->
      <div
      class="block p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700"
      >
        <h5 class="text-3xl font-bold text-gray-900 dark:text-white ml-2">
          รายการคำขอกู้
        </h5>
        <hr class="my-5" />
        <div class="hidden w-full my-5 md:block md:w-auto" id="navbar-default">
          <ul class="font-medium flex flex-col p-4 md:p-0 mt-4 border border-gray-100 rounded-lg bg-gray-50 md:flex-row md:space-x-8 md:mt-0 md:border-0 md:bg-white dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700">
            <li>
              <a href="#" class="block py-2 pl-3 pr-4 text-white bg-blue-700 rounded md:bg-transparent md:text-blue-700 md:p-0 dark:text-white md:dark:text-blue-500" aria-current="page">ทั้งหมด</a>
            </li>
            <li>
              <a href="#" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">คำขอกู้สามัญ</a>
            </li>
            <li>
              <a href="#" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">คำขอกู้ฉุกเฉิน</a>
            </li>
            <!-- <li>
              <a href="#" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Pricing</a>
            </li>
            <li>
              <a href="#" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Contact</a>
            </li> -->
          </ul>
        </div>
        <div class="relative overflow-x-auto shadow-md sm:rounded-lg">
            <table class="w-full text-md text-left text-gray-500 dark:text-gray-400">
                <thead class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
                    <tr>
                        <th scope="col" class="px-6 py-3">
                            ลำดับ
                        </th>
                        <th scope="col" class="px-6 py-3">
                            ชื่อ
                        </th>
                        <th scope="col" class="px-6 py-3">
                            จำนวนเงิน
                        </th>
                        <!-- <th scope="col" class="px-6 py-3">
                            <span class="sr-only">Edit</span>
                        </th> -->
                    </tr>
                </thead>
                <tbody>
                  <tr v-for="i in 5" class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                        <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                            {{ i }}
                        </th>
                        <td class="px-6 py-4">
                            นาย บลาๆๆๆ
                        </td>
                        <td class="px-6 py-4">
                            {{ i*25000 }} THB
                        </td>
                        <td class="px-6 py-4 text-right">
                            <a href="detailborrow" class="font-medium text-blue-600 dark:text-blue-500 hover:underline">ตรวจสอบคำร้อง</a>
                        </td>
                  </tr>
                </tbody>
            </table>
        </div>
      </div>
    </div>
  </section>
</template>
