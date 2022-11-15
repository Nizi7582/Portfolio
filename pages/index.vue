<template>
  <div id="home" class="overflow-hidden">
    <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
  />
    <!--<div class="cursor small z-50"></div>
    <div class="cursor big z-50"></div> -->
    
    <div class="max-w-7xl mx-auto">
      <div class="relative">
        <div class="px-6 py-20 md:px-12 lg:px-7">
          <div class="grid grid-cols-2 px-2 md:px-0">
            <div class="relative pl-20 lg:my-24 xl:my-32 bg-green-500 rounded-tl-3xl pt-12">
              <p class="mt-8 text-gray-200 text-lg font-semibold uppercase mb-4 tracking-widest">Hello my name is</p>

                <h1 class="font-bold text-5xl text-gray-900 md:text-6xl"><span class="police"> Nizaar</span><br><a class=""> Znagui</a></h1>

                <p class="mt-8 text-gray-200 font-semibold text-xl tracking-widest">A <span class="font-extrabold">passionate</span> developper who is<br> always <span class="font-extrabold">curious</span> about web technologies</p>

                <div class="mt-12">
                  <div class="text-2xl ">
                    <a href="#_" class="relative px-6 py-3 font-bold text-black group">
                      <span class="absolute inset-0 w-full h-full transition duration-300 ease-out transform -translate-x-2 -translate-y-2 bg-gray-300 group-hover:translate-x-0 group-hover:translate-y-0"></span>
                      <span class="absolute inset-0 w-full h-full border-4 border-black"></span>
                      <span class="relative uppercase">Check my cv</span>
                    </a>
                  </div>

                </div>

              </div>
              <div class="ml-auto mr-10">
                  <img src="~/assets/nizaar.jpg" class="relative w-full rounded-3xl" alt="food illustration" loading="lazy" width="100" height="450">
              </div>
          </div>
          <div class="h-full bg-gray-100">
            <div clas="">
              <div class="pl-20 -mt-32 pt-20 ">
                <div class="police text-green-400 text-5xl font-semibold">About Me</div>
                
                <div class="pt-6 font-bold text-4xl text-gray-900 md:text-5xl" >
                  My Biography
                </div>
                <div class="bg-gray-900 h-2 w-32 mt-8"></div>
              </div>
              <div class="px-20 pt-12 pb-20">
                <div class="text-gray-900 font-semibold text-2xl">
                  I'm a 18's years old guy, studying and living in France.
                   I was always interested in IT, but decided to make it my life after discovering the web universe.
                    Ready to learn anything to reach the best possible result.
                    Known as cheerful, i always seek the fun in everything
                </div>
              </div>
            </div>
          </div>
          <div class="h-full bg-gray-800">
            <div clas="mx-auto">
              <div class="text-center font-bold text-5xl text-gray-900 md:text-6xl pt-20">
                <div class="police text-green-400 text-5xl font-semibold">These Are</div>
                <div class="text-gray-300 ">My Actual Skills</div>
                <div class="bg-green-400 h-2 w-32 mt-8 mx-auto"></div>
              </div>
              <div>
                <Skills />
              </div>
            </div>
          </div>
          <div class="h-full bg-gray-100">
            <div clas="">
              <div class="pl-20 pt-20 ">
                <div class="police text-green-400 text-5xl font-semibold">About Me</div>
                
                <div class="pt-6 font-bold text-4xl text-gray-900 md:text-5xl" >
                  My Everyday Life
                </div>
                <div class="bg-gray-900 h-2 w-32 mt-8"></div>
              </div>
              <div class="px-20 pt-12 pb-20">
                <section class="overflow-hidden text-gray-700 ">
              <div class="container mx-auto">
                <div class="grid grid-cols-3 -m-1 md:-m-2">
                  <div class="flex flex-wrap group">
                    <div class="w-full p-1 md:p-2">
                      <img alt="gallery" class="block object-cover object-center w-full h-full rounded-lg "
                        src="https://mdbcdn.b-cdn.net/img/Photos/Horizontal/Nature/4-col/img%20(73).webp">
                    </div>
                  </div>
                  <div class="flex flex-wrap">
                    <div class="w-full p-1 md:p-2">
                      <img alt="gallery" class="block object-cover object-center w-full h-full rounded-lg"
                        src="https://mdbcdn.b-cdn.net/img/Photos/Horizontal/Nature/4-col/img%20(74).webp">
                    </div>
                  </div>
                  <div class="flex flex-wrap">
                    <div class="w-full p-1 md:p-2">
                      <img alt="gallery" class="block object-cover object-center w-full h-full rounded-lg"
                        src="https://mdbcdn.b-cdn.net/img/Photos/Horizontal/Nature/4-col/img%20(75).webp">
                    </div>
                  </div>
                  <div class="flex flex-wrap">
                    <div class="w-full p-1 md:p-2">
                      <img alt="gallery" class="block object-cover object-center w-full h-full rounded-lg"
                        src="https://mdbcdn.b-cdn.net/img/Photos/Horizontal/Nature/4-col/img%20(70).webp">
                    </div>
                  </div>
                  <div class="flex flex-wrap">
                    <div class="w-full p-1 md:p-2">
                      <img alt="gallery" class="block object-cover object-center w-full h-full rounded-lg"
                        src="https://mdbcdn.b-cdn.net/img/Photos/Horizontal/Nature/4-col/img%20(76).webp">
                    </div>
                  </div>
                  <div class="flex flex-wrap">
                    <div class="w-full p-1 md:p-2">
                      <img alt="gallery" class="block object-cover object-center w-full h-full rounded-lg"
                        src="https://mdbcdn.b-cdn.net/img/Photos/Horizontal/Nature/4-col/img%20(76).webp">
                    </div>
                  </div>
                </div>
              </div>
            </section>
              </div>
            </div>
          </div>
          <div class="">
            
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      table: []
    }
  }
}
</script>

<style>
.color:hover {
  filter: grayscale(0);
}
</style>