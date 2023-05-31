<template>
    <section class="bg-white dark:bg-gray-900">

        <div class="mx-auto max-w-screen-2xl px-4 lg:px-12 p-6">
            <div class="block p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
                <h2 class="mb-4 text-3xl font-bold text-gray-900 dark:text-white">สมัครสมาชิกสหกรณ์</h2>
                <h2 class="mt-4 mb-2 text-xl font-bold text-gray-900 dark:text-white">ข้อมูลส่วนตัว</h2>
                <form action="#">
                    <div class="grid gap-4 sm:grid-cols-6 sm:gap-6">
                        <div class="sm:col-span-1">
                            <label for="countries"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">คำนำหน้าชื่อ</label>
                            <select id="countries"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500">
                                <option selected>คำนำหน้า</option>
                                <option value="US">นาย</option>
                                <option value="CA">นาง</option>
                                <option value="FR">นางสาว</option>
                                <option value="DE">ดร.</option>
                            </select>
                        </div>
                        <div class="sm:col-span-2">
                            <label for="name"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ชื่อ</label>
                            <input type="text" name="name" id="name"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" required>
                        </div>
                        <div class="sm:col-span-2">
                            <label for="name"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">สกุล</label>
                            <input type="text" name="name" id="name"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" required>
                        </div>
                        <div class="sm:col-span-1">
                            <label for="name"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">วัน-เดือน-ปีเกิด</label>
                            <div class="relative">
                                <div class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none">
                                    <svg aria-hidden="true" class="w-5 h-5 text-gray-500 dark:text-gray-400"
                                        fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                                        <path fill-rule="evenodd"
                                            d="M6 2a1 1 0 00-1 1v1H4a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V6a2 2 0 00-2-2h-1V3a1 1 0 10-2 0v1H7V3a1 1 0 00-1-1zm0 5a1 1 0 000 2h8a1 1 0 100-2H6z"
                                            clip-rule="evenodd"></path>
                                    </svg>
                                </div>
                                <input datepicker type="text"
                                    class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full pl-10 p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                                    placeholder="Select date">
                            </div>
                        </div>

                    </div>
                    <div class="grid gap-4 sm:grid-cols-4 sm:gap-6 py-5">
                        <div class="w-full">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">บ้านเลขที่</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" required>
                        </div>
                        <div class="w-full">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">หมู่ที่</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" required>
                        </div>
                        <div class="w-full">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ถนน</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" required>
                        </div>
                        <div class="w-full">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ตำบล</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" required>
                        </div>
                        <div class="w-full">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">อำเภอ</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" required>
                        </div>
                        <div class="w-full">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">จังหวัด</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" required>
                        </div>
                        <div class="w-full">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">รหัสไปรษณีย์</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" required>
                        </div>
                        <div class="w-full">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">เบอร์โทรศัพท์</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" required>
                        </div>
                        <div class="sm:col-span-2">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">เลชบัตรประจำตัวประชาชน</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" required>
                        </div>
                        <div class="sm:col-span-2">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">เลขที่บัญชีธนาคารกรุงไทย</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" required>
                        </div>

                    </div>

                    <h2 class="mt-4 mb-2 text-xl font-bold text-gray-900 dark:text-white">ข้อมูลสังกัด</h2>
                    <div class="grid gap-4 sm:grid-cols-8 sm:gap-6">
                        <div class="sm:col-span-2">
                            <label for="countries"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ประเภท</label>
                            <select id="countries"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500">
                                <option selected value="ข้าราชการ">ข้าราชการ</option>
                                <option value="ลูกจ้างประจำ">ลูกจ้างประจำ</option>
                                <option value="พนักงานราชการ">พนักงานราชการ</option>
                                <option value="พนักงานกระทรวงสาธารณสุบ">พนักงานกระทรวงสาธารณสุบ</option>
                            </select>
                        </div>
                        <div class="sm:col-span-2">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ตำแหน่ง</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" required>
                        </div>
                        <div class="sm:col-span-2">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">แผนก</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" required>
                        </div>
                        <div class="sm:col-span-2">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">เงินเดือนประจำตำแหน่ง</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" required>
                        </div>
                    </div>
                    <h2 class="mt-4 mb-2 text-xl font-bold text-gray-900 dark:text-white">สหกรณ์</h2>
                    <div class="grid gap-4 sm:grid-cols-8 sm:gap-6">
                        <div class="sm:col-span-2">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ประสงค์ส่งเงินค่าหุ้น
                                (มูลละค่าหุ้น 10.00 บาท)</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="อัตราเดือนละ" required>
                        </div>
                        <div class="sm:col-span-6">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">หมายเหตุ:
                                หากจะแสดงจำนงสูงกว่าอัตราที่กำหนดไว้</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" required>
                        </div>
                    </div>
                    <div class="flex items-center mt-4">
                        <input id="default-checkbox" type="checkbox" value=""
                            class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 rounded focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
                        <label for="default-checkbox"
                            class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">ท่านยอมรับการดำเนินการของสหกรณ์</label><u class="ml-2 text-sm font-medium text-blue-900 dark:text-gray-300"> อ่านเอกสารเพิ่มเติม </u>
                    </div>
                    <button type="submit"
                        class="inline-flex items-center px-5 py-2.5 mt-4 sm:mt-4 text-sm font-medium text-center text-white bg-primary-700 rounded-lg focus:ring-4 focus:ring-primary-200 dark:focus:ring-primary-900 hover:bg-primary-800">
                        สมัครสมาชิก
                    </button>
                </form>
            </div>
    </div>
</section></template>