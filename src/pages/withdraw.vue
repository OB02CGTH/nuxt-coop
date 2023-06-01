<template>
    <section>
        <div class="mx-auto max-w-screen-2xl px-4 lg:px-12 p-6">
            <div class="max-w-screen-xl px-4 mx-auto lg:px-12 w-full">
                <div
                    class="max-w-screen-xl px-4 mx-auto lg:px-12 mt-5 p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
                    <form>
                        <div class="grid gap-6 mb-6 md:grid-cols-2">
                            <div>
                                <div class="mb-2">เลขที่บัญชี :
                                    <span
                                        class="bg-gray-100  text-gray-800 text-xg font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-gray-300">
                                        25XXX-XX-XXX</span>
                                </div>
                                <div>รหัสสมาชิก :
                                    <span
                                        class="bg-gray-100  text-gray-800 text-xg font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-gray-300">
                                        XXX-XX-XXX</span>
                                </div>
                            </div>
                            <div class="flex justify-end">
                                <div>
                                    <div class="mb-2">ประเภทบัญชี :
                                        <span
                                            class="bg-gray-100  text-gray-800 text-xg font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-gray-300">
                                            ออมทรัพย์</span>
                                    </div>
                                    <div>ยอดเงินคงเหลือ :
                                        <span
                                            class="bg-gray-100  text-gray-800 text-xg font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-gray-300">
                                            50,000</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <hr class="my-5" />
                        <div class="grid gap-6 mb-6 md:grid-cols-2">
                            <div>
                                <label for="first_name"
                                    class="text-lg block mb-2 text-sm font-medium text-gray-900 dark:text-white">ชื่อ</label>
                                <input type="text" id="disabled-input" aria-label="disabled input"
                                    class="mb-6 bg-gray-100 border border-gray-300 text-gray-900 text-1xl rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 cursor-not-allowed dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-gray-400 dark:focus:ring-blue-500 dark:focus:border-blue-500"
                                    value="นาย กล้วย" disabled>
                            </div>
                            <div>
                                <label for="last_name"
                                    class="text-lg block mb-2 text-sm font-medium text-gray-900 dark:text-white">สกุล</label>
                                <input type="text" id="disabled-input" aria-label="disabled input"
                                    class="mb-6 bg-gray-100 border border-gray-300 text-gray-900 text-1xl rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 cursor-not-allowed dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-gray-400 dark:focus:ring-blue-500 dark:focus:border-blue-500"
                                    value="หอม" disabled>
                            </div>
                        </div>
                        <div class="mb-6">
                            <label class="text-2xl font-medium">ช่องทางจ่ายเงิน</label>
                        </div>
                        <div class="grid gap-6 mb-6 md:grid-cols-2">
                            <div class="flex items-center pl-4 border border-gray-200 rounded dark:border-gray-700">
                                <input id="bordered-radio-1" type="radio" value="" name="bordered-radio"
                                    class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
                                <label for="bordered-radio-1"
                                    class="w-full py-4 ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">โอนผ่านธนาคาร
                                </label>
                            </div>
                            <div class="flex items-center pl-4 border border-gray-200 rounded dark:border-gray-700">
                                <input checked id="bordered-radio-2" type="radio" value="" name="bordered-radio"
                                    class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
                                <label for="bordered-radio-2"
                                    class="w-full py-4 ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">เช็ค
                                </label>
                            </div>
                        </div>
                        <div class="grid gap-6 mb-6 md:grid-cols-2">
                            <div>
                                <label for="first_name"
                                    class="text-1xl block mb-2 text-sm font-medium text-gray-900 dark:text-white">เลขที่บัญชี</label>
                                <input type="text" id="first_name"
                                    class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                                    placeholder="2xxxx-xxx-xx" required>
                            </div>
                            <div>
                                <label for="first_name"
                                    class="text-1xl block mb-2 text-sm font-medium text-gray-900 dark:text-white">จำนวนเงิน</label>
                                <input type="text" id="first_name"
                                    class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                                    placeholder="THB" required>
                            </div>
                        </div>
                        <button type="submit"
                            class="mr-5 text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm w-full sm:w-auto px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">ยกเลิก</button>
                        <button type="submit" data-modal-target="popup-modal" data-modal-toggle="popup-modal"
                            class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm w-full sm:w-auto px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">บันทึก</button>
                    </form>
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
                        <h3 ยืนยันการบันทึก class="mb-5 text-lg font-normal text-gray-500 dark:text-gray-400">ยืนยันบันทึกการถอน</h3>
                        <button data-modal-hide="popup-modal" type="button"
                            class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm w-full sm:w-auto px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                            ยกลง
                        </button>                        
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
  