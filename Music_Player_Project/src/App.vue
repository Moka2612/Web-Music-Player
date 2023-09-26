<template>
  <section class="min-h-screen max-h-screen w-full bg-[#26302f] p-2">
    <div class="flex gap-2 mb-2">
      <BaseNavigationBar />
      <BaseMain />
    </div>
    <BaseMusicPlayer />
  </section>
</template>

<script setup>
import BaseNavigationBar from "./components/BaseNavigationBar.vue";
import BaseMain from "./components/BaseMain.Vue";
import BaseMusicPlayer from "./components/BaseMusicPlayer.vue";
</script>
