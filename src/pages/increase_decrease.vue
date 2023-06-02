<template>
    <section>
        <div class="mx-auto max-w-screen-2xl px-4 lg:px-12 p-6">
            <!-- Start coding here -->
            <div class="block p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
                <h5 class="text-3xl font-bold text-gray-900 dark:text-white ml-2">
                    การจัดขอเพิ่ม-ลดค่าหุ้น
                </h5>
                <section class="bg-white dark:bg-gray-900">
                    <div class=" px-4 py-8 mx-auto lg:py-16">

                       
  <div class="mt-3 flex justify-start">
    <form>
                            <label for="default-search"
                                class="mb-100 text-sm font-medium text-gray-900 sr-only dark:text-white">ค้นหา</label>
                            <div class="relative">
                                <div class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none">
                                    <svg aria-hidden="true" class="w-4 h-4 text-gray-500 dark:text-gray-400" fill="none"
                                        stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                            d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
                                    </svg>
                                </div>
                                <input type="search" id="default-search"
                                    class="block w-100 p-2 pl-10 text-sm text-gray-900 border border-gray-300 rounded-lg bg-gray-50 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                                    placeholder="เลขที่สมาชิก หรือ ชื่อ-สกุล" required>
                                <button type="submit"
                                    class="mt-100 text-white absolute left-102 bottom-0.5 bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-4 py-2 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">ค้นหา</button>
                            </div>
                        </form>
    <div class="ml-178 flex justify-start"><!-- Modal toggle -->
         <button data-modal-target="defaultModal" data-modal-toggle="defaultModal"
                                class="block text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
                                type="button">
                                รายการคำขอ
                            </button>

<!-- Modal toggle -->
  <button data-modal-target="defaultModal" data-modal-toggle="defaultModal1" 
                                class="ml-5  block text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
                                type="button">
                                เสนออนุมัติ
                            </button></div>
         

                            <!-- Main modal -->
                            <div id="defaultModal" tabindex="-1" aria-hidden="true"
                                class="fixed top-0 left-0 right-0 z-50 hidden w-full p-4 overflow-x-hidden overflow-y-auto md:inset-0 h-[calc(100%-1rem)] max-h-full">
                                <div class="relative w-full max-w-2xl max-h-full">
                                    <!-- Modal content -->
                                    <div class="relative bg-white rounded-lg shadow dark:bg-gray-700">
                                        <!-- Modal header -->
                                        <div
                                            class="flex items-start justify-between p-4 border-b rounded-t dark:border-gray-600">
                                            <h3 class="text-xl font-semibold text-gray-900 dark:text-white">
                                                รายการคำขอเพิ่ม-ลดค่าหุ้น
                                            </h3>
                                            <button type="button"
                                                class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-600 dark:hover:text-white"
                                                data-modal-hide="defaultModal">
                                                <svg aria-hidden="true" class="w-5 h-5" fill="currentColor"
                                                    viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                                                    <path fill-rule="evenodd"
                                                        d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                                                        clip-rule="evenodd"></path>
                                                </svg>
                                                <span class="sr-only">Close modal</span>
                                            </button>
                                        </div>
                                        <!-- Modal body -->
                                        <div class="p-6 space-y-6">
                                            <section>
    <div class="mx-auto max-w-screen-2xl px-4 lg:px-12 p-6">
      <!-- Start coding here -->
      <div
      class="block p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700"
      >
       
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
                        <td class="px-6 py-3">
                            นาย บลาๆๆๆ
                        </td>
                        <td class="px-6 py-4 text-right">
                            <a href="detailborrow" class="font-medium text-blue-600 dark:text-blue-500 hover:underline">ดูรายละเอียด</a>
                        </td>
                  </tr>
                </tbody>
            </table>
            
        </div>
      </div>
    </div>
  </section>
                                        </div>
                                    </div>
                                </div>
                            </div>



                            <!-- Main modal -->
                            <div id="defaultModal1" tabindex="-1" aria-hidden="true"
                                class="fixed top-0 left-0 right-0 z-50 hidden w-full p-4 overflow-x-hidden overflow-y-auto md:inset-0 h-[calc(100%-1rem)] max-h-full">
                                <div class="relative w-full max-w-2xl max-h-full">
                                    <!-- Modal content -->
                                    <div class="relative bg-white rounded-lg shadow dark:bg-gray-700">
                                        <!-- Modal header -->
                                        <div
                                            class="flex items-start justify-between p-4 border-b rounded-t dark:border-gray-600">
                                            <h3 class="text-xl font-semibold text-gray-900 dark:text-white">
                                                รายการเสนออนุมัติ
                                            </h3>
                                            <button type="button"
                                                class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-600 dark:hover:text-white"
                                                data-modal-hide="defaultModal1">
                                                <svg aria-hidden="true" class="w-5 h-5" fill="currentColor"
                                                    viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                                                    <path fill-rule="evenodd"
                                                        d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                                                        clip-rule="evenodd"></path>
                                                </svg>
                                                <span class="sr-only">Close modal</span>
                                            </button>
                                        </div>
                                        <!-- Modal body -->
                                        <div class="p-6 space-y-6">
                                            <section>
    <div class="mx-auto max-w-screen-2xl px-4 lg:px-12 p-6">
      <!-- Start coding here -->
      <div
      class="block p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700"
      >
       
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
                            สถานะ
                        </th>
                        <th scope="col" class="px-6 py-3">
                            
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
                        <td class="px-6 py-3">
                            นาย บลาๆๆๆ
                        </td>
                        <td class="px-6 py-3">
                            <span class="bg-blue-100 text-blue-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded-full dark:bg-blue-900 dark:text-blue-300">รออนุมัติ</span>
                        </td>
                        <td class="px-6 py-4 text-right">
                            <a href="detailborrow" class="font-medium text-blue-600 dark:text-blue-500 hover:underline">แก้ไข</a>
                        </td>
                  </tr>
                </tbody>
            </table>
            
        </div>
      </div>
    </div>
  </section>
                                        </div>
                                    </div>
                                </div>
                            </div>
  </div>
                            
                     
<div class="mt-3 mb-5 mx-auto max-w-screen-2xl p-5 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
    
<div class="grid grid-cols-2 gap-2">
        <div>
            ชื่อ-สกุล : นาย รักชาติ เพื่อไทย
        </div>
        <div>
            เลขที่สมาชิก : 00015577
        </div>
        <div>
            ตำแหน่ง : พนักงานประจำ
        </div>
        <div>
            เงินเดือน : 15000
        </div>
    </div>

</div>
<div class="flex items-center mb-4 ml-2">
    <input id="default-radio-1" type="radio" value="" name="default-radio" class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
    <label for="default-radio-1" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">ขอเพิ่ม</label>
</div>
<div class="flex items-center ml-2">
    <input checked id="default-radio-2" type="radio" value="" name="default-radio" class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
    <label for="default-radio-2" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">ขอลด</label>
</div>
                       
<div class="mt-5 w-167">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ส่งค่าหุ้นเดือนละ</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                value="" placeholder="กรอกเงินเดือนของสมาชิก" required="">
                        </div>
                        <div class="w-167 mt-5">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ส่งเป็นเดือนละ</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                value="" placeholder="กรอกเงินเดือนของสมาชิก" required="">
                        </div>
                        <div class="w-167 mt-5">
                            <label for="brand"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">มีผลตั้งแต่เดือน</label>
                            <input type="text" name="brand" id="brand"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                value="" placeholder="กรอกวัน/เดือน/ปี" required="">
                        </div>
<div class="flex items-center space-x-4 mt-5">
                            <button type="submit"
                                class="text-white bg-primary-700 hover:bg-primary-800 focus:ring-4 focus:outline-none focus:ring-primary-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800">
                                บันทึก
                            </button>
                            <button type="button"
                                class="text-red-600 inline-flex items-center hover:text-white border border-red-600 hover:bg-red-600 focus:ring-4 focus:outline-none focus:ring-red-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:border-red-500 dark:text-red-500 dark:hover:text-white dark:hover:bg-red-600 dark:focus:ring-red-900">
                                <svg class="w-5 h-5 mr-1 -ml-1" fill="currentColor" viewBox="0 0 20 20"
                                    xmlns="http://www.w3.org/2000/svg">
                                    <path fill-rule="evenodd"
                                        d="M9 2a1 1 0 00-.894.553L7.382 4H4a1 1 0 000 2v10a2 2 0 002 2h8a2 2 0 002-2V6a1 1 0 100-2h-3.382l-.724-1.447A1 1 0 0011 2H9zM7 8a1 1 0 012 0v6a1 1 0 11-2 0V8zm5-1a1 1 0 00-1 1v6a1 1 0 102 0V8a1 1 0 00-1-1z"
                                        clip-rule="evenodd"></path>
                                </svg>
                                ยกเลิก
                            </button>
                        </div>
                    </div>
                    
                       



                       
                        
                   </section>
                   </div>
                </div>
            </section>
            </template>
  