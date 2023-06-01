<template>
    <section>
        <div class="mx-auto max-w-screen-2xl px-4 lg:px-12 p-6">
            <div class="max-w-screen-xl px-4 mx-auto lg:px-12 w-full">
                <div
                    class="max-w-screen-xl px-4 mx-auto lg:px-12 mt-5 p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
                    <h5 class="text-3xl font-bold text-gray-900 dark:text-white ml-2">
                        คำขอรายการถอน
                    </h5>
                    <hr class="my-5" />
                    <div class="relative overflow-x-auto shadow-md sm:rounded-lg">
                        <table class="w-full text-md text-left text-gray-500 dark:text-gray-400">
                            <thead class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
                                <tr>
                                    <th scope="col" class="p-4">
                                        ลำดับ
                                    </th>
                                    <th scope="col" class="px-6 py-3">
                                        ชื่อ
                                    </th>
                                    <th scope="col" class="px-6 py-3">
                                        ยอดเงิน
                                    </th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr
                                    class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                                    <th scope="row"
                                        class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                                        1
                                    </th>
                                    <td class="px-6 py-4">
                                        นาย กล้วย หอม
                                    </td>
                                    <td class="px-6 py-4">
                                        5,000
                                    </td>
                                </tr>
                                <tr
                                    class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                                    <th scope="row"
                                        class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                                        2
                                    </th>
                                    <td class="px-6 py-4">
                                        นาย แก้ว สีเขียว
                                    </td>
                                    <td class="px-6 py-4">
                                        5,000
                                    </td>
                                </tr>
                                <tr
                                    class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                                    <th scope="row"
                                        class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                                        3
                                    </th>
                                    <td class="px-6 py-4">
                                        นาย เหลือ แดง
                                    </td>
                                    <td class="px-6 py-4">
                                        5,000
                                    </td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                    <button type="button" data-modal-target="popup-modal" data-modal-toggle="popup-modal"
                        class="mt-4 text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">ปิดยอด</button>
                </div>
            </div>
        </div>
        <!-- Main modal -->
        <div id="popup-modal" tabindex="-1"
            class="fixed top-0 left-0 right-0 z-50 hidden p-4 overflow-x-hidden overflow-y-auto md:inset-0 h-[calc(100%-1rem)] max-h-full">
            <div class="relative w-full max-w-md max-h-full">
                <div class="relative bg-white rounded-lg shadow dark:bg-gray-700">
                    <div class="p-6 text-center">
                        <svg aria-hidden="true" class="mx-auto mb-4 text-gray-400 w-14 h-14 dark:text-gray-200" fill="none"
                            stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M12 8v4m0 4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                        </svg>
                        <h3 class="mb-5 text-lg font-normal text-gray-500 dark:text-gray-400">
                            ต้องการปิดยอดส่งฝ่ายบัญชีหรือไม่
                        </h3>                        
                            <button data-modal-hide="popup-modal" type="button"
                                class="mr-5 text-gray-500 bg-white hover:bg-gray-100 focus:ring-4 focus:outline-none focus:ring-gray-200 rounded-lg border border-gray-200 text-sm font-medium px-5 py-2.5 hover:text-gray-900 focus:z-10 dark:bg-gray-700 dark:text-gray-300 dark:border-gray-500 dark:hover:text-white dark:hover:bg-gray-600 dark:focus:ring-gray-600">
                                ตกลง
                            </button>
                        <button data-modal-hide="popup-modal" type="button"
                            class="text-white bg-red-600 hover:bg-red-800 focus:ring-4 focus:outline-none focus:ring-red-300 dark:focus:ring-red-800 font-medium rounded-lg text-sm inline-flex items-center px-5 py-2.5 text-center mr-2">
                            ยกเลิก</button>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
  