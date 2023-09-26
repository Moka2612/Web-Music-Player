<template>
  <section class="w-96 bg-[#051a16] rounded-xl flex flex-col relative">
    <a class="mx-auto flex items-center py-10 mb-5" href="#">
      <img
        class="h-14 w-14 bg-[#38d9a9] rounded-full mr-2"
        src="../ImgLogo/logo.png"
        alt="Logo App"
      />
      <h1 class="text-2xl text-white italic">Tune Music</h1>
    </a>

    <!-- begin div -->
    <div class="w-full flex flex-col mb-20">
      <h1 class="text-xl text-white mb-8 pl-14">Brower</h1>

      <!-- begin div -->
      <div
        class="group w-full h-16 flex items-center pl-14 hover:bg-[rgba(56,217,169,0.3)] duration-200"
      >
        <div
          class="box h-16 w-1 bg-[#38d9a9] rounded-r-md absolute left-0 opacity-0 group-hover:opacity-100"
        ></div>

        <i class="fa-solid fa-house fa-xl mr-6 group-hover:text-gray-100"></i>
        <p class="text-base group-hover:text-gray-100">Home</p>
      </div>
      <!-- end div -->

      <!-- begin div -->
      <div
        class="group w-full h-16 flex items-center pl-14 hover:bg-[rgba(56,217,169,0.3)] duration-200"
      >
        <div
          class="box h-16 w-1 bg-[#38d9a9] rounded-r-md absolute left-0 opacity-0 group-hover:opacity-100"
        ></div>

        <i
          class="fa-solid fa-regular fa-compact-disc fa-xl mr-6 group-hover:text-gray-100"
        ></i>
        <p class="text-base group-hover:text-gray-100">Album</p>
      </div>
      <!-- end div -->

      <!-- begin div -->
      <div
        class="group w-full h-16 flex items-center pl-14 hover:bg-[rgba(56,217,169,0.3)] duration-200"
      >
        <div
          class="box h-16 w-1 bg-[#38d9a9] rounded-r-md absolute left-0 opacity-0 group-hover:opacity-100"
        ></div>
        <i class="fa-regular fa-user fa-xl mr-6 group-hover:text-gray-100"></i>
        <p class="text-base group-hover:text-gray-100">Artists</p>
      </div>
      <!-- end div -->

      <!-- begin div -->
      <div
        class="group w-full h-16 flex items-center pl-14 hover:bg-[rgba(56,217,169,0.3)] duration-200"
      >
        <div
          class="box h-16 w-1 bg-[#38d9a9] rounded-r-md absolute left-0 opacity-0 group-hover:opacity-100"
        ></div>
        <i class="fa-solid fa-list fa-xl mr-6 group-hover:text-gray-100"></i>
        <p class="text-base group-hover:text-gray-100">Playlist</p>
      </div>
      <!-- end div -->
    </div>
    <!-- end div -->

    <!-- begin div -->
    <div class="w-full flex flex-col pb-20">
      <h1 class="text-xl text-white mb-8 pl-14">My Library</h1>

      <!-- begin div -->
      <div
        class="group w-full h-16 flex items-center pl-14 hover:bg-[rgba(56,217,169,0.3)] duration-200"
      >
        <div
          class="box h-16 w-1 bg-[#38d9a9] rounded-r-md absolute left-0 opacity-0 group-hover:opacity-100"
        ></div>
        <i class="fa-regular fa-heart fa-xl mr-6 group-hover:text-gray-100"></i>
        <p class="text-base group-hover:text-gray-100">Favourite Songs</p>
      </div>
      <!-- end div -->

      <!-- begin div -->
      <div
        class="group w-full h-16 flex items-center pl-14 hover:bg-[rgba(56,217,169,0.3)] duration-200"
      >
        <div
          class="box h-16 w-1 bg-[#38d9a9] rounded-r-md absolute left-0 opacity-0 group-hover:opacity-100"
        ></div>
        <i
          class="fa-solid fa-reply-all fa-xl mr-6 group-hover:text-gray-100"
        ></i>
        <p class="text-base group-hover:text-gray-100">Recently Played</p>
      </div>
      <!-- end div -->
    </div>
    <!-- end div -->
  </section>
</template>
