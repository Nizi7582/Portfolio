<template>
    <div>
        <div class="items-center flex flex-wrap">
            <div class="w-full md:w-4/12 ml-auto mr-auto px-4 container_outer_img img-inner">
                <img alt="..." class="max-w-md rounded-lg shadow-lg container_img" src="~/assets/nizaar.jpg">
            </div>
            <div class="w-full md:w-5/12 ml-auto mr-auto px-4">
                <div class="md:pr-12">
                <div class="text-pink-600 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-green-300 mt-8">
                    <i class="fas fa-rocket text-xl"></i>
                </div>
                <h3 class="text-3xl font-semibold title">About me</h3>
                <p class="mt-4 text-lg leading-relaxed text-blueGray-500 par">
                    I'm a passionate developper who is always curious about the web technologies. 
                    Known as cheerful, i always seek the fun in everything.
                </p>
                <ul class="list-none mt-6">
                    <li class="py-2">
                    <div class="flex items-center">
                        <div>
                        <span class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-pink-600 bg-pink-200 mr-3"><i class="fas fa-fingerprint"></i></span>
                        </div>
                        <div>
                        <h4 class="text-blueGray-500">
                            Carefully crafted components
                        </h4>
                        </div>
                    </div>
                    </li>
                    <li class="py-2">
                    <div class="flex items-center">
                        <div>
                        <span class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-pink-600 bg-pink-200 mr-3"><i class="fab fa-html5"></i></span>
                        </div>
                        <div>
                        <h4 class="text-blueGray-500">Amazing page examples</h4>
                        </div>
                    </div>
                    </li>
                    <li class="py-2">
                    <div class="flex items-center">
                        <div>
                        <span class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-pink-600 bg-pink-200 mr-3"><i class="far fa-paper-plane"></i></span>
                        </div>
                        <div>
                        <h4 class="text-blueGray-500">Dynamic components</h4>
                        </div>
                    </div>
                    </li>
                </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.text-main {
  color: rgba(203, 233, 35, 0.993)
}
.border-main {
  border-color: rgba(222, 255, 34, 0.993)
}
.bg-main {
  background-color: rgb(70, 80, 14)
}

.overlay {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  height: 100%;
  z-index: -10;
  background-color: var(--contrast-color);
}

.container {
  display: flex;
  height: 100vh;
  justify-content: space-around;
  align-items: center;
  color: #fff;
  animation: expand .8s ease forwards;
  background-color: var(--secondary-color);
  position: relative;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  transition: all .8s ease;
}

.container_content {
 width: 50%;
}

.container_content_inner {
  width: 80%;
  margin-left: 80px;
}

.container_outer_img {
  margin: 50px;
  width: 50%;
  overflow: hidden;
}   
    
.container_img {
  width: 100%;
  animation: slideIn 1.5s ease-in-out forwards;
}

.par {
  height: auto;
  overflow: hidden;
}

p{
  line-height: 28px;
  transform: translateY(300px);
  animation: slideUp .8s ease-in-out forwards .8s;
}

.btns {
  height: 100%;
  position: relative;
  width: 150px;
  overflow: hidden;
}

.btns_more {
  background: transparent;
  border: 1px solid var(--contrast-color);
  border-radius: 50px;
  padding: 8px 12px;
  color: #BF307F;
  font-size: 16px;
  text-transform: uppercase;
  position: relative;
  margin-top: 15px;
  outline: none;
  transform: translateY(50px);
  animation: slideUp .8s ease-in-out  forwards 1s;
}

.title {
  overflow: hidden;
  height: auto;
}

h1 {
    font-size: 40px;
    color: var(--contrast-color);
    margin-bottom: 20px;
    transform: translateY(100px);
    animation: slideUp .8s ease forwards .5s;
}

@keyframes slideIn {
  0% {
    transform: translateX(500px) scale(.2);
  }
  100% {
    transform: translateX(0px) scale(1);
  }
}

@keyframes slideUp {
  0% {
    transform: translateY(300px);
  }
  100% {
    transform: translateY(0px);
  }
}

@keyframes expand {
  0% {
    transform: translateX(1400px);
  }
  100% {
    transform: translateX(0px);
  }
}
</style>