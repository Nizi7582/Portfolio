<template>
  <div class="section-fluid-main pb-14">
    <div class="text-center font-bold text-5xl text-gray-900 md:text-6xl pt-32 pb-14">
      <div class="police text-green-400 text-5xl font-semibold">Discover</div>
      <div class="text-gray-300">My projects</div>
      <div class="bg-green-400 h-2 w-32 mt-8 mx-auto"></div>
    </div>
    <div class="section-row">
      <nuxt-link to="./getafish" class="section-col">
        <div class="section">
          <div class="section-in">
            <img src="~/assets/projects/bg-getafish.png" alt="" />
          </div>
        </div>
      </nuxt-link>
      <div class="hover-text">
        <h2>GetAFish</h2>
      </div>
      <nuxt-link to="./drawin" class="section-col">
        <div class="section">
          <div class="section-in">
            <img src="~/assets/projects/bg-drawin.png" alt="" />
          </div>
        </div>
      </nuxt-link>
      <div class="hover-text">
        <h2>DraWin</h2>
      </div>
      <nuxt-link to="./dropkit" class="section-col">
        <div class="section">
          <div class="section-in">
            <img src="~/assets/projects/bg-dropkit.png" alt="" />
          </div>
        </div>
      </nuxt-link>
      <div class="hover-text">
        <h2>Dropkit</h2>
      </div>
      <nuxt-link to="./unsacpourtous" class="section-col">
        <div class="section">
          <div class="section-in">
            <img src="~/assets/projects/bg-unsacpourtous.png" alt="" />
          </div>
        </div>
      </nuxt-link>
      <div class="hover-text">
        <h2>Unsacpourtous</h2>
      </div>
      <nuxt-link to="./alloccasions" class="section-col">
        <div class="section">
          <div class="section-in">
            <img src="~/assets/projects/bg-alloccasions.png" alt="" />
          </div>
        </div>
      </nuxt-link>
      <div class="hover-text">
        <h2>Alloccasions</h2>
      </div>
      <nuxt-link to="./troi" class="section-col">
        <div class="section">
          <div class="section-in">
            <img src="~/assets/projects/bg-troi.png" alt="" />
          </div>
        </div>
      </nuxt-link>
      <div class="hover-text">
        <h2>Troi</h2>
      </div>
    </div>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css?family=Poppins:400,500,600,700,800,900');
*,
*::before,
*::after {
  box-sizing: border-box;
}
body {
  font-family: 'Poppins', sans-serif;
  font-weight: 400;
  font-size: 15px;
  line-height: 1.7;
  color: #fff;
  background-color: #1f2029;
  margin: 0;
  padding: 0;
  overflow-x: none;
}
p {
  font-family: 'Poppins', sans-serif;
  font-weight: 400;
  font-size: 16px;
  line-height: 1.7;
  color: #fff;
  margin: 0;
}
.section-fluid-main {
  position: relative;
  display: block;
  overflow: hidden;
  width: calc(100% - 40px);
  padding-right: 15px;
  padding-left: 15px;
  margin-right: auto;
  margin-left: auto;
  padding-left: 100px 0;
  padding-right: 100px 0;
}
.section-row {
  display: -ms-flexbox;
  display: flex;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  margin-right: -15px;
  margin-left: -15px;
}
.section-row:hover .section-col {
  opacity: 0.1;
}
.section-col {
  position: relative;
  width: 100%;
  -ms-flex: 0 0 50%;
  flex: 0 0 50%;
  max-width: 50%;
  transition: opacity 250ms linear;
}
.section-row .section-col:hover {
  opacity: 1;
}
.section {
  position: relative;
  display: block;
  width: 100%;
  overflow: hidden;
  cursor: pointer;
  padding: 15px;
}
.section-in {
  position: relative;
  display: block;
  width: 100%;
  overflow: hidden;
  border-radius: 6px;
  cursor: pointer;
}
.section-in img {
  display: block;
  width: 100%;
  height: 320px;
  transition: transform 250ms linear;
}
.section-col:hover .section-in img {
  transform: scale(1.1) rotate(-3deg);
}

.hover-text {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  overflow: hidden;
  z-index: 100;
  pointer-events: none;
  display: -webkit-inline-flex;
  display: -ms-inline-flexbox;
  display: inline-flex;
  -webkit-align-items: center;
  -moz-align-items: center;
  -ms-align-items: center;
  align-items: center;
  -webkit-justify-content: center;
  -moz-justify-content: center;
  -ms-justify-content: center;
  justify-content: center;
  -ms-flex-pack: center;
  text-align: center;
  -ms-flex-item-align: center;
  align-self: center;
  mix-blend-mode: difference;
}
.hover-text h2 {
  font-family: 'Poppins', sans-serif;
  font-weight: 800;
  font-size: 8vw;
  line-height: 1;
  color: #fff;
  opacity: 0;
  transform: scale(0.8);
  transition: transform 250ms linear, opacity 250ms ease;
}
.section-col:hover + .hover-text h2 {
  opacity: 1;
  transform: scale(1);
}
</style>
