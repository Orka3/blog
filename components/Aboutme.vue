<template>
  <div class="fullpage1">
    <div class="flex flex-row justify-center">
      <div class="introduction w-2/3 py-10 pl-4 flex-column justify-center">
        <div class="text-white font-semibold text-lg hover:text-blue-800">
          ORKA | developer
        </div>
        <div class="mt-5 text-gray-400 prose text-base keepall">
          안녕하세요, 다양한 것을 배우고 있는 개발자, ORKA입니다. <br />
          새로운 것을 배우고, 새로운 사람들과 새로운 경험을 하는 것을
          좋아합니다. <br />
          이 공간은 그런 저를 나타내기 위한 것들이 담겨있습니다. <br />
          주로 공부한 것들, 경험한 프로젝트들, 그리고 회고록이 업로드됩니다.<br />
          제가 배우고 느낀 것들이 당신에게 도움이 됐으면 좋겠습니다:>
        </div>
      </div>
      <div data-aos="fade-in">
        <div class="imagecenter">
          <img
            :src="require('assets/resources/Whale1.jpg')"
            style="height: 500px; width: 800px"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.imagecenter {
  margin-top: 10%;
  margin-right: 100px;
}
.introduction {
  margin-top: 10%;
  margin-left: 15%;
}
p {
  text-decoration-color: white;
}
.fullpage1 {
  height: 100vh;
  width: 100vw;
  background-color: black;
}
</style>
