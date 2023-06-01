<template>
  <section>
    <div>
      <div class="flex justify-center mt-5">
        <div
          class="w-full w-6xl bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700"
        >
          <div>
            <label
              for="password"
              class="block m-5 text-4xl font-bold text-gray-900 dark:text-white"
              >การขอรับสวัสดิการณ์</label
            >
            <hr class="my-3" />
            <label
              for="password"
              class="block mx-5 text-2xl font-thin text-gray-900 dark:text-white"
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
            <div>
              <div class="relative overflow-x-auto">
                <table
                  class="w-full text-sm text-left text-gray-500 dark:text-gray-400"
                >
                  <thead
                    class="text-xs text-gray-900 uppercase dark:text-gray-400"
                  >
                    <tr>
                      <th scope="col" class="px-6 py-3 text-2xl font-thin">
                        ประเภทสวัสดิการณ์
                      </th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr class="bg-white dark:bg-gray-800">
                      <th
                        scope="row"
                        class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white"
                      >
                        ทุนการศึกษาบุตร
                      </th>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">
                        <a
                          href="#"
                          class="font-medium text-blue-600 dark:text-blue-500 hover:underline"
                          >ขอรับสวัสดิการ</a
                        >
                      </td>
                    </tr>
                    <tr class="bg-white dark:bg-gray-800">
                      <th
                        scope="row"
                        class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white"
                      >
                        ทุนสาธารณประโยชน์เพื่อบำเพ็ญกุศลศพ บิดา มารดา คู่สมรส
                        และบุตร
                      </th>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">
                        <a
                          href="#"
                          class="font-medium text-blue-600 dark:text-blue-500 hover:underline"
                          >ขอรับสวัสดิการ</a
                        >
                      </td>
                    </tr>
                    <tr class="bg-white dark:bg-gray-800">
                      <th
                        scope="row"
                        class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white"
                      >
                        ทุนสาธารณประโยชน์เพื่อช่วยเหลือประสบอัคคีภัย
                      </th>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">
                        <a
                          href="#"
                          class="font-medium text-blue-600 dark:text-blue-500 hover:underline"
                          >ขอรับสวัสดิการ</a
                        >
                      </td>
                    </tr>
                    <tr class="bg-white dark:bg-gray-800">
                      <th
                        scope="row"
                        class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white"
                      >
                        ทุนสาธารณประโยชน์เพื่อช่วยเหลือกรณีประสบภัยพิบัติ วาตภัย
                        อุทกภัย
                      </th>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">
                        <a
                          href="#"
                          class="font-medium text-blue-600 dark:text-blue-500 hover:underline"
                          >ขอรับสวัสดิการ</a
                        >
                      </td>
                    </tr>
                    <tr class="bg-white dark:bg-gray-800">
                      <th
                        scope="row"
                        class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white"
                      >
                        เงินช่วยเหลือสมาชิกประสบอุบัติเหตุ
                      </th>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">
                        <a
                          href="#"
                          class="font-medium text-blue-600 dark:text-blue-500 hover:underline"
                          >ขอรับสวัสดิการ</a
                        >
                      </td>
                    </tr>
                    <tr class="bg-white dark:bg-gray-800">
                      <th
                        scope="row"
                        class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white"
                      >
                        เงินบำรุงขวัญสมาชิกอายุครบ 60 ปีบริบูรณ์
                      </th>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">
                        <a
                          href="#"
                          class="font-medium text-blue-600 dark:text-blue-500 hover:underline"
                          >ขอรับสวัสดิการ</a
                        >
                      </td>
                    </tr>
                    <tr class="bg-white dark:bg-gray-800">
                      <th
                        scope="row"
                        class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white"
                      >
                        เงินสวัสดิการสมาชิกอาวุโส
                      </th>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">
                        <a
                          href="#"
                          class="font-medium text-blue-600 dark:text-blue-500 hover:underline"
                          >ขอรับสวัสดิการ</a
                        >
                      </td>
                    </tr>
                    <tr class="bg-white dark:bg-gray-800">
                      <th
                        scope="row"
                        class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white"
                      >
                        เงินสงเคราะห์สมาชิกถึงแก่กรรม
                      </th>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">
                        <a
                          href="#"
                          class="font-medium text-blue-600 dark:text-blue-500 hover:underline"
                          >ขอรับสวัสดิการ</a
                        >
                      </td>
                    </tr>
                    <tr class="bg-white dark:bg-gray-800">
                      <th
                        scope="row"
                        class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white"
                      >
                        เงินสวัสดิการช่วยเหลือค่าคลอดบุตร
                      </th>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">
                        <a
                          href="#"
                          class="font-medium text-blue-600 dark:text-blue-500 hover:underline"
                          >ขอรับสวัสดิการ</a
                        >
                      </td>
                    </tr>
                    <tr class="bg-white dark:bg-gray-800">
                      <th
                        scope="row"
                        class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white"
                      >
                        เงินสวัสดิการช่วยเหลือสมาชิกติดเชื้อไวรัส COVID-19
                      </th>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">---</td>
                      <td class="px-6 py-4">
                        <a
                          href="#"
                          class="font-medium text-blue-600 dark:text-blue-500 hover:underline"
                          >ขอรับสวัสดิการ</a
                        >
                      </td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
