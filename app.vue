<template>
  <div>
    <NuxtRouteAnnouncer />
    <div :style="img_banner1" class="photoMainBox_ rounded-Lg"></div>
    <div :style="img_banner2" class="photoMainBox_ rounded-Lg"></div>
    <div :style="img_banner3" class="photoMainBox_ rounded-Lg"></div>
    <div :style="img_banner4" class="photoMainBox_ rounded-Lg"></div>
    <div :style="img_banner5" class="photoMainBox_ rounded-Lg"></div>
    <NuxtWelcome />
  </div>
</template>
<script setup lang="ts">
import img_banner1_ from "/VCIcon_s.jpg";
import img_banner2_ from "~/public/Westgort_Anticipation_17_months.jpg";
import img_banner3_ from "~/public/history-02.jpg";
import img_banner4_ from "~/public/img-32.jpg";

let img_banner1 = {
  backgroundImage: `url(/Westgort_Anticipation_17_months.jpg)`,
  backgroundRepeat: "no-repeat",
  backgroundSize: "cover",
  backgroundPosition: "center",
}
let img_banner5 = {
  backgroundImage: `url(~/assets/Westgort_Anticipation_17_months.jpg)`,
  backgroundRepeat: "no-repeat",
  backgroundSize: "cover",
  backgroundPosition: "center",
}
  let img_banner2 = {
    backgroundImage: `url(${img_banner2_})`,
    backgroundRepeat: "no-repeat",
    backgroundSize: "cover",
    backgroundPosition: "center",
}
  let img_banner3 = {
    backgroundImage: `url(${img_banner3_})`,
    backgroundRepeat: "no-repeat",
    backgroundSize: "cover",
    backgroundPosition: "center",
}
  let img_banner4 = {
    backgroundImage: `url(/img-32.jpg)`,
    backgroundRepeat: "no-repeat",
    backgroundSize: "cover",
    backgroundPosition: "center",
}
</script>
<style>

.photoMainBox_{
  width: 50px;
  height: 50px;
  z-index: 100;
  border: 1px;
}
</style>