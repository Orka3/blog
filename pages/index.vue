<template>
  <div>
    <div>
      <div class="fullpage">
        <Header />
        <VueRealWave
          wavePosition="bottom"
          :waveLayerCount="4"
          :space="370"
          :waveGap="150"
          :waveHeight="151"
          :waveColor="[
            'rgb(125, 128, 137)',
            'rgb(176, 188, 188)',
            'rgb(45, 55, 65)',
            'black',
          ]"
        >
          <div class="flex justify-center items-center">
            <div>
              <p>ORKA</p>
              <div class="flex justify-center items-center">
                <p1>the developer</p1>
              </div>
            </div>
          </div>
        </VueRealWave>
      </div>
    </div>
    <div class="fullpage bg-black">
      <Aboutme />
    </div>
    <div class="fullpage bg-black">
      <Category />
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

<style>
.fullpage {
  height: 100%;
  width: 100%;
}
.fullpage1 {
  height: 100vh;
  width: 100vw;
  background-color: black;
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
