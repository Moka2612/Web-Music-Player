<template>
  <section class="music-player-box flex justify-between">
    <div class="h-full basis[30%] flex gap-3 items-center">
      <img
        class="h-16 w-16 rounded-xl object-cover object-center"
        src="../ImgLogo/album-test.jpg"
        alt=""
      />
      <div>
        <h1 class="text-lg text-white">Music Name</h1>
        <h2 class="text-sm">Artist Name</h2>
      </div>
    </div>

    <div class="h-full basis-[40%] flex flex-col justify-center gap-3">
      <div class="flex justify-center gap-8">
        <button><i class="fa-solid fa-repeat"></i></button>
        <button><i class="fa-solid fa-backward-step"></i></button>
        <button><i class="fa-solid fa-play"></i></button>
        <button><i class="fa-solid fa-forward-step"></i></button>
        <button><i class="fa-solid fa-shuffle"></i></button>
      </div>

      <div class="flex justify-center items-center gap-2">
        <p>2:00</p>
        <input
          class="playtime-slider"
          type="range"
          min="0"
          max="100"
          value="50"
        />
        <p>4:00</p>
      </div>
    </div>

    <div class="h-full basis[30%] flex items-center gap-2">
      <i class="fa-solid fa-volume-high"></i>
      <input class="volum-slider" type="range" min="0" max="100" value="50" />
    </div>
  </section>
</template>

<style scoped>
.music-player-box {
  width: 100%;
  height: 7.2rem;
  padding: 0.5rem 1.5rem;
  background-color: rgb(38, 48, 47, 0.5);
  backdrop-filter: blur(5px);
  position: fixed;
  bottom: 0;
  left: 0;
  transition: all 0.3s;
}

input[type="range"] {
  overflow: hidden;
  width: 100%;
  height: 7px;
  border-radius: 5px;
  -webkit-appearance: none;
  background-color: #ccc;
}

input[type="range"]::-webkit-slider-thumb {
  -webkit-appearance: none;
  width: 15px;
  height: 15px;
  border-radius: 100%;
  cursor: pointer;
  background: #38d9a9;
  box-shadow: -1000px 0 0 1000px #38d9a9;
}

input[type="range"]::-webkit-slider-thumb:hover {
  cursor: pointer;
  background: #fff;
  box-shadow: -1000px 0 0 1000px #099268;
}

input[type="range"]:hover {
  background-color: #9b9b9b;
}
</style>

<!-- /** Fire fox*/
/* input[type="range"]::-moz-range-progress {
  background-color: #43e5f7; 
}
input[type="range"]::-moz-range-track {  
  background-color: #9a905d;
} -->
