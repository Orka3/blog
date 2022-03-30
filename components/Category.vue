<template>
  <div class="fullpage bg-black flex justify-between">
    <div
      class="justify-center"
      data-aos="fade-down"
      style="height: 30vh; width: 100vw"
    >
      <img
        :src="require('~/assets/resources/Whale2.jpg')"
        class="whale2img"
        style="height: 29vh; width: 200px"
      />
      <div class="bottom py-10" style="background-color: black; height: 70vh">
        <div class="container grid grid-cols-3 gap-15">
          <div class="center">
            <p2> memoir</p2>
            <img
              :src="require('~/assets/resources/Moon.PNG')"
              class="border border-black hover:border-indigo-300 rounded-full"
              style="height: 150px"
            />
          </div>
          <div class="center">
            <p2> study</p2>
            <nuxt-link
              :to="{ path: '/Study' }"
              class="text-gray-700 text-sm font-semibold"
            >
              <img
                :src="require('assets/resources/Earth.PNG')"
                class="border border-black hover:border-indigo-300 rounded-full"
                style="height: 230px"
            /></nuxt-link>
          </div>
          <div class="center">
            <p2> project</p2>
            <img
              :src="require('assets/resources/Planet.PNG')"
              class="border border-black hover:border-indigo-300 rounded-full"
              style="height: 180px"
            />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
.fullpage1 {
  height: 100vh;
  width: 100vw;
  background-color: black;
}
.whale2img {
  margin-left: 55%;
  margin-top: 1vh;
}
.planetimg {
  height: 100px;
  width: 100px;
}
.bottom {
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  align-items: center;
}
.center {
  display: flex;
  flex-direction: column;
  justify-items: center;
  align-items: center;
}
p {
  font-family: Playfair Display;
  font-size: 50px;
}
p1 {
  font-family: Inspiration;
  font-size: 30px;
}
p2 {
  font-family: Dancing Script;
  font-size: 30px;
  color: white;
}
</style>
