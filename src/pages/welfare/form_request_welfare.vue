<template>
  <section>
    <div>
      <div class="flex justify-center my-10">
        <div
          class="w-full w-6xl bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700"
        >
          <div>
            <label
              for="password"
              class="block p-5 text-4xl font-bold text-gray-900 dark:text-white"
              >การขอรับสวัสดิการณ์</label
            >
            <hr class="my-3" />
            <label
              for="password"
              class="block px-5 text-2xl font-thin text-gray-900 dark:text-white"
              >ข้อมูลสมาชิก</label
            >
            <div class="grid grid-cols-4 p-5">
              <div class="flex justify-around items-left items-center">
                <img
                  class="w-24 h-24 mb-3 rounded-full shadow-lg"
                  src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7e/Circle-icons-profile.svg/2048px-Circle-icons-profile.svg.png"
                  alt="Bonnie image"
                />
              </div>
              <div class="col-span-3">
                <div class="grid grid-cols-2">
                  <h5
                    class="mb-1 text-xl font-medium text-gray-900 dark:text-white"
                  >
                    ชื่อ-นามสกุล: นาย สมหมาย ใจดี
                  </h5>
                  <span class="text-xl text-gray-900 dark:text-gray-400"
                    >รหัสสมาชิก: 1355487958</span
                  >
                  <span class="text-xl text-gray-900 dark:text-gray-400"
                    >บัตรประชาชน: 1339966445845</span
                  >
                  <span class="text-xl text-gray-900 dark:text-gray-400"
                    >อายุการเป็นสมาชิก: 5 ปี</span
                  >
                  <span class="text-xl text-gray-900 dark:text-gray-400"
                    >วันเกิด: 17 มกราคม 2521</span
                  >
                </div>
              </div>
            </div>
            <hr class="w-full p-4" />
            <label
              for="password"
              class="block px-5 text-2xl font-thin text-gray-900 dark:text-white"
              >คำขอความประสงค์</label
            >
            <div class="grid grid-cols-2 p-5">
              <div class="mb-6 px-2 w-full">
                <label
                  for="base-input"
                  class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                  >ชื่อ-นามสกุล ผู้ถึงแก่กรรม</label
                >
                <input
                  type="text"
                  id="base-input"
                  class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                />
              </div>
              <div class="mb-6 px-2 w-full">
                <label
                  for="base-input"
                  class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                  >วันที่เสียชีวิต</label
                >

                <div class="relative max-w-full">
                  <div
                    class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none"
                  >
                    <svg
                      aria-hidden="true"
                      class="w-5 h-5 text-gray-500 dark:text-gray-400"
                      fill="currentColor"
                      viewBox="0 0 20 20"
                      xmlns="http://www.w3.org/2000/svg"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M6 2a1 1 0 00-1 1v1H4a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V6a2 2 0 00-2-2h-1V3a1 1 0 10-2 0v1H7V3a1 1 0 00-1-1zm0 5a1 1 0 000 2h8a1 1 0 100-2H6z"
                        clip-rule="evenodd"
                      ></path>
                    </svg>
                  </div>
                  <input
                    datepicker
                    datepicker-autohide
                    type="text"
                    class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full pl-10 p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                    placeholder="เลือกวันที่"
                  />
                </div>
              </div>
              <div class="mb-6 px-2 w-full">
                <label
                  for="base-input"
                  class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                  >ธนาคารกรุงไทย จำกัด(มหาชน) เลขที่บัญชี</label
                >
                <input
                  type="text"
                  id="base-input"
                  class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                />
              </div>
              <div class="px-2 w-full">
                <label
                  for="base-input"
                  class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                  >เกี่ยวข้องเป็น</label
                >
                <div class="flex">
                  <ul
                    class="items-center w-full text-sm font-medium text-gray-900 bg-white border border-gray-200 rounded-lg sm:flex dark:bg-gray-700 dark:border-gray-600 dark:text-white"
                  >
                    <li
                      class="w-full border-b border-gray-200 sm:border-b-0 sm:border-r dark:border-gray-600"
                    >
                      <div class="flex items-center pl-3">
                        <input
                          id="horizontal-list-radio-married"
                          type="radio"
                          value=""
                          name="list-radio"
                          class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-700 dark:focus:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500"
                        />
                        <label
                          for="horizontal-list-radio-married"
                          class="w-full py-3 ml-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                          >คู่สมรส
                        </label>
                      </div>
                    </li>
                    <li
                      class="w-full border-b border-gray-200 sm:border-b-0 sm:border-r dark:border-gray-600"
                    >
                      <div class="flex items-center pl-3">
                        <input
                          id="horizontal-list-radio-father"
                          type="radio"
                          value=""
                          name="list-radio"
                          class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-700 dark:focus:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500"
                        />
                        <label
                          for="horizontal-list-radio-father"
                          class="w-full py-3 ml-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                          >บิดา</label
                        >
                      </div>
                    </li>
                    <li
                      class="w-full border-b border-gray-200 sm:border-b-0 sm:border-r dark:border-gray-600"
                    >
                      <div class="flex items-center pl-3">
                        <input
                          id="horizontal-list-radio-mother"
                          type="radio"
                          value=""
                          name="list-radio"
                          class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-700 dark:focus:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500"
                        />
                        <label
                          for="horizontal-list-radio-mother"
                          class="w-full py-3 ml-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                          >มารดา</label
                        >
                      </div>
                    </li>
                    <li class="w-full dark:border-gray-600">
                      <div class="flex items-center pl-3">
                        <input
                          id="horizontal-list-radio-child"
                          type="radio"
                          value=""
                          name="list-radio"
                          class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-700 dark:focus:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500"
                        />
                        <label
                          for="horizontal-list-radio-child"
                          class="w-full py-3 ml-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                          >บุตรที่ยังไม่บรรลุ</label
                        >
                      </div>
                    </li>
                  </ul>
                </div>
              </div>
              <div class="px-2 w-full">
                <label
                  for="base-input"
                  class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                  >โดยขอรับเป็น</label
                >
                <div class="flex">
                  <ul
                    class="items-center w-full text-sm font-medium text-gray-900 bg-white border border-gray-200 rounded-lg sm:flex dark:bg-gray-700 dark:border-gray-600 dark:text-white"
                  >
                    <li
                      class="w-full border-b border-gray-200 sm:border-b-0 sm:border-r dark:border-gray-600"
                    >
                      <div class="flex items-center pl-3">
                        <input
                          id="horizontal-list-radio-check"
                          type="radio"
                          value=""
                          name="list-radio"
                          class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-700 dark:focus:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500"
                        />
                        <label
                          for="horizontal-list-radio-check"
                          class="w-full py-3 ml-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                          >เช็คเงินสด
                        </label>
                      </div>
                    </li>
                    <li class="w-full dark:border-gray-600">
                      <div class="flex items-center pl-3">
                        <input
                          id="horizontal-list-radio-transfer"
                          type="radio"
                          value=""
                          name="list-radio"
                          class="w-4 h-4 text-blue-600 bg-gray-100 border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-700 dark:focus:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500"
                        />
                        <label
                          for="horizontal-list-radio-transfer"
                          class="w-full py-3 ml-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                          >โอนเข้า</label
                        >
                      </div>
                    </li>
                  </ul>
                </div>
              </div>
              <div class="px-2 w-full">
                <label
                  for="base-input"
                  class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                  >บันทึกข้อมูลเพื่อตรวจสอบเอกสาร</label
                >
                <button
                  type="button"
                  class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-10 py-3 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800"
                >
                  บันทึก
                </button>
              </div>
            </div>
            <hr class="w-full p-2" />
            <div class="px-5 pb-5">
              <span>
                ด้วย ข้าพเจ้า (นายสมหมาย ใจดี) ตำแหน่ง (แพทย์)
                สมาชิกสหกรณ์ฯเลขทะเบียนที่ (1355487958) หน่วยงาน (ข้าราชการ)
                สังกัด (โรงพยาบาลศรีสะเกษ)
                มีความประสงค์ขอเบิกสวัสดิการสมาชิกเพื่อการฌาปนกิจศพ (บิดา)
                นิติภาวะ ชื่อ-สกุล (สมปอง ยอมใจ) ซึ่งได้ถึงแก่กรรม เมื่อวันที่
                (20/05/2566) โดยขอรับเงินดังกล่าวเป็น (โอนเข้า) ธนาคารกรุงไทย
                จำกัด (มหาชน) เลขที่บัญชี (1222544557) พร้อมแนบเอกสารหลักฐาน
              </span>
            </div>
            <hr class="w-full p-4" />
            <div class="px-4 pb-4">
              <h2
                class="mb-2 text-lg font-semibold text-gray-900 dark:text-white"
              >
                เอกสารหลักฐานที่ใช้
              </h2>

              <div class="relative overflow-x-auto">
                <table
                  class="w-full text-sm text-left text-gray-500 dark:text-gray-400"
                >
                  <thead
                    class="text-xs text-gray-900 uppercase dark:text-gray-400"
                  >
                    <tr>
                      <th scope="col" class="px-6 py-3"></th>
                      <th scope="col" class="px-6 py-3">อัพโหลดเอกสาร</th>
                      <th scope="col" class="px-6 py-3">ผ่าน/ไม่ผ่าน</th>
                      <th scope="col" class="px-6 py-3">เอกสารจริง</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr class="bg-white dark:bg-gray-800">
                      <th
                        scope="row"
                        class="px-6 py-2 font-medium text-gray-900 whitespace-nowrap dark:text-white"
                      >
                        สำเนาบัตรประชาชนของผู้เสียชีวิต
                      </th>
                      <td class="px-6 py-2">
                        <a
                          href="#"
                          class="font-medium text-blue-600 dark:text-blue-500 hover:underline"
                          >อัพโหลด</a
                        >
                      </td>
                      <td class="px-6 py-2">
                        <svg
                          class="w-4 h-4 mr-1.5 text-gray-400 dark:text-green-400 flex-shrink-0"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="1.5"
                          viewBox="0 0 24 24"
                          xmlns="http://www.w3.org/2000/svg"
                          aria-hidden="true"
                        >
                          <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            d="M15 12H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z"
                          ></path>
                        </svg>
                      </td>
                      <td class="px-6 py-2">
                        <svg
                          class="w-4 h-4 mr-1.5 text-gray-400 dark:text-green-400 flex-shrink-0"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="1.5"
                          viewBox="0 0 24 24"
                          xmlns="http://www.w3.org/2000/svg"
                          aria-hidden="true"
                        >
                          <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            d="M15 12H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z"
                          ></path>
                        </svg>
                      </td>
                    </tr>
                    <tr class="bg-white dark:bg-gray-800">
                      <th
                        scope="row"
                        class="px-6 py-2 font-medium text-gray-900 whitespace-nowrap dark:text-white"
                      >
                        สำเนาทะเบียนบ้านของผู้เสียชีวิต (ประทับตราคำว่า"ตาย")
                      </th>
                      <td class="px-6 py-2">
                        <a
                          href="#"
                          class="font-medium text-blue-600 dark:text-blue-500 hover:underline"
                          >ตรวจสอบแล้ว</a
                        >
                      </td>
                      <td class="px-6 py-2">
                        <svg
                          class="w-4 h-4 mr-1.5 text-green-500 dark:text-green-400 flex-shrink-0"
                          fill="currentColor"
                          viewBox="0 0 20 20"
                          xmlns="http://www.w3.org/2000/svg"
                        >
                          <path
                            fill-rule="evenodd"
                            d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                            clip-rule="evenodd"
                          ></path>
                        </svg>
                      </td>
                      <td class="px-6 py-2">
                        <svg
                          class="w-4 h-4 mr-1.5 text-green-500 dark:text-green-400 flex-shrink-0"
                          fill="currentColor"
                          viewBox="0 0 20 20"
                          xmlns="http://www.w3.org/2000/svg"
                        >
                          <path
                            fill-rule="evenodd"
                            d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                            clip-rule="evenodd"
                          ></path>
                        </svg>
                      </td>
                    </tr>
                    <tr class="bg-white dark:bg-gray-800">
                      <th
                        scope="row"
                        class="px-6 py-2 font-medium text-gray-900 whitespace-nowrap dark:text-white"
                      >
                        สำเนาใบมรณบัตร
                      </th>
                      <td class="px-6 py-2">
                        <a
                          href="#"
                          class="font-medium text-blue-600 dark:text-blue-500 hover:underline"
                          >รอการตรวจสอบ</a
                        >
                      </td>
                      <td class="px-6 py-2">
                        <svg
                          class="w-4 h-4 mr-1.5 text-gray-400 dark:text-green-400 flex-shrink-0"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="1.5"
                          viewBox="0 0 24 24"
                          xmlns="http://www.w3.org/2000/svg"
                          aria-hidden="true"
                        >
                          <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            d="M15 12H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z"
                          ></path>
                        </svg>
                      </td>
                      <td class="px-6 py-2">
                        <svg
                          class="w-4 h-4 mr-1.5 text-gray-400 dark:text-green-400 flex-shrink-0"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="1.5"
                          viewBox="0 0 24 24"
                          xmlns="http://www.w3.org/2000/svg"
                          aria-hidden="true"
                        >
                          <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            d="M15 12H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z"
                          ></path>
                        </svg>
                      </td>
                    </tr>
                    <tr class="bg-white dark:bg-gray-800">
                      <th
                        scope="row"
                        class="px-6 py-2 font-medium text-gray-900 whitespace-nowrap dark:text-white"
                      >
                        สำเนาบัตรประชาชนของสมาชิก
                      </th>
                      <td class="px-6 py-2">
                        <a
                          href="#"
                          class="font-medium text-blue-600 dark:text-blue-500 hover:underline"
                          >ตรวจสอบแล้ว</a
                        >
                      </td>
                      <td class="px-6 py-2">
                        <svg
                          class="w-4 h-4 mr-1.5 text-red-400 flex-shrink-0"
                          fill="currentColor"
                          viewBox="0 0 20 20"
                          xmlns="http://www.w3.org/2000/svg"
                        >
                          <path
                            fill-rule="evenodd"
                            d="M10 18a8 8 0 100-16 8 8 0 000 16zM8.707 7.293a1 1 0 00-1.414 1.414L8.586 10l-1.293 1.293a1 1 0 101.414 1.414L10 11.414l1.293 1.293a1 1 0 001.414-1.414L11.414 10l1.293-1.293a1 1 0 00-1.414-1.414L10 8.586 8.707 7.293z"
                            clip-rule="evenodd"
                          ></path>
                        </svg>
                      </td>
                      <td class="px-6 py-2">
                        <svg
                          class="w-4 h-4 mr-1.5 text-red-400 flex-shrink-0"
                          fill="currentColor"
                          viewBox="0 0 20 20"
                          xmlns="http://www.w3.org/2000/svg"
                        >
                          <path
                            fill-rule="evenodd"
                            d="M10 18a8 8 0 100-16 8 8 0 000 16zM8.707 7.293a1 1 0 00-1.414 1.414L8.586 10l-1.293 1.293a1 1 0 101.414 1.414L10 11.414l1.293 1.293a1 1 0 001.414-1.414L11.414 10l1.293-1.293a1 1 0 00-1.414-1.414L10 8.586 8.707 7.293z"
                            clip-rule="evenodd"
                          ></path>
                        </svg>
                      </td>
                    </tr>
                    <tr class="bg-white dark:bg-gray-800">
                      <th
                        scope="row"
                        class="px-6 py-2 font-medium text-gray-900 whitespace-nowrap dark:text-white"
                      >
                        สำเนาทะเบียนบ้านของสมาชิก
                      </th>
                      <td class="px-6 py-2">
                        <a
                          href="#"
                          class="font-medium text-blue-600 dark:text-blue-500 hover:underline"
                          >ตรวจสอบแล้ว</a
                        >
                      </td>
                      <td class="px-6 py-2">
                        <svg
                          class="w-4 h-4 mr-1.5 text-green-500 dark:text-green-400 flex-shrink-0"
                          fill="currentColor"
                          viewBox="0 0 20 20"
                          xmlns="http://www.w3.org/2000/svg"
                        >
                          <path
                            fill-rule="evenodd"
                            d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                            clip-rule="evenodd"
                          ></path>
                        </svg>
                      </td>
                      <td class="px-6 py-2">
                        <svg
                          class="w-4 h-4 mr-1.5 text-red-400 flex-shrink-0"
                          fill="currentColor"
                          viewBox="0 0 20 20"
                          xmlns="http://www.w3.org/2000/svg"
                        >
                          <path
                            fill-rule="evenodd"
                            d="M10 18a8 8 0 100-16 8 8 0 000 16zM8.707 7.293a1 1 0 00-1.414 1.414L8.586 10l-1.293 1.293a1 1 0 101.414 1.414L10 11.414l1.293 1.293a1 1 0 001.414-1.414L11.414 10l1.293-1.293a1 1 0 00-1.414-1.414L10 8.586 8.707 7.293z"
                            clip-rule="evenodd"
                          ></path>
                        </svg>
                      </td>
                    </tr>
                    <tr class="bg-white dark:bg-gray-800">
                      <th
                        scope="row"
                        class="px-6 py-2 font-medium text-gray-900 whitespace-nowrap dark:text-white"
                      >
                        สำเนาทะเบียนสมรส (ในกรณีสมรส)
                      </th>
                      <td class="px-6 py-2">
                        <a
                          href="#"
                          class="font-medium text-blue-600 dark:text-blue-500 hover:underline"
                          >อัพโหลด</a
                        >
                      </td>
                      <td class="px-6 py-2">
                        <svg
                          class="w-4 h-4 mr-1.5 text-gray-400 dark:text-green-400 flex-shrink-0"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="1.5"
                          viewBox="0 0 24 24"
                          xmlns="http://www.w3.org/2000/svg"
                          aria-hidden="true"
                        >
                          <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            d="M15 12H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z"
                          ></path>
                        </svg>
                      </td>
                      <td class="px-6 py-2">
                        <svg
                          class="w-4 h-4 mr-1.5 text-gray-400 dark:text-green-400 flex-shrink-0"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="1.5"
                          viewBox="0 0 24 24"
                          xmlns="http://www.w3.org/2000/svg"
                          aria-hidden="true"
                        >
                          <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            d="M15 12H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z"
                          ></path>
                        </svg>
                      </td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
          <hr class="w-full p-4" />

          <label
            for="password"
            class="block px-5 text-sm font-thin text-gray-500 dark:text-white"
            ><span class="text-red-600">*</span
            >การส่งคำร้องข้างต้นเป็นเพียงการส่งตรวจสอบเอกสาร
            แต่ยังต้องนำส่งเอกสารจริงถึงสหกรณ์อยู่</label
          >
          <div class="flex justify-end">
            <button
              type="button"
              class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800"
            >
              ส่งคำร้อง
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
