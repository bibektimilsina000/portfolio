<template>
  <div class="">
    <div class="bg-primary p-5 pt10 h-screen w-20 md:w-52 shadow-lime-900">
      <div class="h-20 flex-auto">
        <h1 class="text-white p-5 text-4xl">B T</h1>
      </div>

      <div class="pt-10 space-y-10">
        <div class="inline-flex hover:bg-green cursor-pointer p-2 rounded-full">
          <i class="fa-solid fa-house text-white text-4xl"></i>
          <h1 class="hidden md:flex px-5 pt-2 hover:text-xl text-white">
            Home
          </h1>
        </div>
        <div class="inline-flex hover:bg-green cursor-pointer p-2 rounded-full">
          <i class="fa-solid fa-address-card text-white text-4xl"></i>
          <h1 class="hidden md:flex px-5 pt-2 text-xl text-white">About</h1>
        </div>
        <div class="inline-flex hover:bg-green p-2 cursor-pointer rounded-full">
          <i
            class="fa-solid fa-briefcase cursor-pointer text-white text-4xl"
          ></i>
          <h1
            class="hidden md:flex px-5 pt-2 text-xl cursor-pointer text-white"
          >
            Portfolio
          </h1>
        </div>
        <div class="inline-flex hover:bg-green cursor-pointer p-2 rounded-full">
          <i class="fa-solid fa-address-card text-white text-4xl"></i>
          <h1 class="hidden md:flex px-5 pt-2 text-xl text-white">Contact</h1>
        </div>
      </div>
      <div class="px-3 mt-10">
        <i class="fa-brands fa-facebook text-white text-xl hover:text-3xl"></i>
        <i class="fa-brands fa-github text-white text-xl hover:text-3xl"></i>
        <i class="fa-brands fa-instagram text-white text-xl hover:text-3xl"></i>
      </div>

      <div>
        <div class="mt-10 m-auto p-0 flex space-x-0.5">
          <i class="fa-regular fa-copyright text-blue-500 py-1"></i>
          <h1 class="text-blue-500">All right reserved.</h1>
        </div>
        <div class="text-white p-3">Bibek Timilsina</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SideBar",
};
</script>
