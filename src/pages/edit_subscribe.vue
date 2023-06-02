<template>
    <section class="bg-white dark:bg-gray-900">
        <div class="mx-auto max-w-screen-2xl px-4 lg:px-12 p-6">
            <div class="block p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
                <h2 class="mb-4 text-3xl font-bold text-gray-900 dark:text-white">สมัครสมาชิกสหกรณ์</h2>
                <h2 class="mt-4 mb-2 text-xl font-bold text-gray-900 dark:text-white">ข้อมูลส่วนตัว</h2>
                <form action="#">
                    <div class="grid gap-4 sm:grid-cols-4 sm:gap-6">
                        <div class="sm:col-span-1">
                            <label for="countries"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">คำนำหน้าชื่อ</label>
                            <select id="countries"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500">
                                <option selected value="US">นาย</option>
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
                                placeholder="" value="กิตติพิชญ์" required>
                        </div>
                        <div class="sm:col-span-2">
                            <label for="name"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">สกุล</label>
                            <input type="text" name="name" id="name"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" value="เสนานุช" required>
                        </div>
                        <div class="sm:col-span-1">
                            <label for="name"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">วัน-เดือน-ปีเกิด</label>


                            <input datepicker type="text"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full pl-10 p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                                placeholder="09/07/2542">

                        </div>

                    </div>
                    <div class="grid gap-4 sm:grid-cols-4 sm:gap-6">
                        <div class="w-full">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">บ้านเลขที่</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" value="1997" required>
                        </div>
                        <div class="w-full">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">หมู่ที่</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" value="12" required>
                        </div>
                        <div class="w-full">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ถนน</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" value="ขอนแก่น-เลย" required>
                        </div>
                        <div class="w-full">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ตำบล</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" value="ในเมือง" required>
                        </div>
                        <div class="w-full">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">อำเภอ</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" value="เมือง" required>
                        </div>
                        <div class="w-full">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">จังหวัด</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" value="ขอนแก่น" required>
                        </div>
                        <div class="w-full">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">รหัสไปรษณีย์</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" value="40000" required>
                        </div>
                        <div class="w-full">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">เบอร์โทรศัพท์</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" value="0899876565" required>
                        </div>
                        <div class="sm:col-span-2">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">เลชบัตรประจำตัวประชาชน</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" value="1423232456765" required>
                        </div>
                        <div class="sm:col-span-2">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">เลขที่บัญชีธนาคารกรุงไทย</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" value="0-0111-2222-1" required>
                        </div>

                    </div>

                    <h2 class="mt-4 mb-2 text-xl font-bold text-gray-900 dark:text-white">ข้อมูลสังกัด</h2>
                    <div class="grid gap-4 sm:grid-cols-4 sm:gap-6">
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
                                placeholder="" value="หมอลำ" required>
                        </div>
                        <div class="sm:col-span-2">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">แผนก</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" value="วงกลาง" required>
                        </div>
                        <div class="sm:col-span-2">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">เงินเดือนประจำตำแหน่ง</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="" value="10000" required>
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
                                placeholder="อัตราเดือนละ" value="100" required>
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
                    <h2 class="mt-4 mb-2 text-xl font-bold text-gray-900 dark:text-white">เงื่อนไข</h2>
                    <div class="flex items-center pl-4 border border-gray-200 rounded dark:border-gray-700">
                        <input checked id="bordered-checkbox-2" type="checkbox" value="" name="bordered-checkbox"
                            class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 rounded focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
                        <label for="bordered-checkbox-2"
                            class="w-full py-4 ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Checked
                            state</label>
                    </div>
                    <div class="flex items-center pl-4 border border-gray-200 rounded dark:border-gray-700">
                        <input checked id="bordered-checkbox-2" type="checkbox" value="" name="bordered-checkbox"
                            class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 rounded focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
                        <label for="bordered-checkbox-2"
                            class="w-full py-4 ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Checked
                            state</label>
                    </div>
                    <div class="flex items-center pl-4 border border-gray-200 rounded dark:border-gray-700">
                        <input checked id="bordered-checkbox-2" type="checkbox" value="" name="bordered-checkbox"
                            class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 rounded focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
                        <label for="bordered-checkbox-2"
                            class="w-full py-4 ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Checked
                            state</label>
                    </div>
                    <div
                        class="flex flex-col flex-shrink-0 space-y-3 md:flex-row md:items-center lg:justify-end md:space-y-0 md:space-x-3 mt-6">
                        <a type="button" href="/request_subscribe"
                            class="flex items-center justify-center px-4 py-2 text-sm font-medium text-white rounded-lg bg-red-700 hover:bg-red-800 focus:ring-4 focus:ring-red-300 dark:bg-red-600 dark:hover:bg-red-700 focus:outline-none dark:focus:ring-red-800">
                            ไม่ผ่าน
                        </a>
                        <a type="button" href="/request_subscribe"
                            class="flex items-center justify-center px-4 py-2 text-sm font-medium text-white rounded-lg bg-primary-700 hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 dark:bg-primary-600 dark:hover:bg-primary-700 focus:outline-none dark:focus:ring-primary-800">
                            ผ่าน
                        </a>
                    </div>
                </form>
            </div>
        </div>
    </section>
</template>