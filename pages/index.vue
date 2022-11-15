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
        <div class="px-6 pt-20 md:px-12 lg:px-7">
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
                <div class="police text-green-500 text-5xl font-semibold">About Me</div>
                
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
            <section class="bg-gray-800 dark:text-gray-100 pb-10">
              <div class="text-center font-bold text-5xl text-gray-900 md:text-6xl pt-20">
                <div class="police text-green-400 text-5xl font-semibold">Check</div>
                <div class="text-gray-300 ">My projects</div>
                <div class="bg-green-400 h-2 w-32 mt-8 mx-auto"></div>
              </div>
              <div class="">
                <div class="max-w-5xl py-12 mx-auto">
                  <div class="grid grid-cols-2 gap-5">
                    <div
                        class="mt-5 bg-opacity-50 border border-gray-100 rounded shadow-lg bg-gradient-to-b from-gray-200 backdrop-blur-20 to-gray-50  ">
                        <div class="flex flex-row px-2 py-3 mx-3">
                            <div class="flex flex-col justify-center items-center w-full mt-1 mb-2">
                              <img src="~/assets/projects/unsacpourtous.webp" class="w-12 h-12" >
                              <div class="text-2xl text-gray-800 font-bold pt-1">Dropkit</div>
                            </div>
                        </div>

                        <div class="flex justify-center text-sm font-medium text-gray-400">
                          <img class="shadow-2xl object-cover border-t-2 border-b-2 border-gray-800 h-72" src="~/assets/projects/bg-dropkit.png">
                        </div>

                        <div class="mb-3 border-t border-gray-50 ">
                            <div class="flex flex-wrap justify-start mx-5 mt-6 text-sm font-semibold gap-2">
                                <div class="flex mb-2 text-gray-700 border rounded-md px-3 py-2 bg-gray-800 text-main">NuxtJS</div>
                                <div class="flex mb-2 text-gray-700 border rounded-md px-3 py-2 bg-gray-800 text-main">TailwindCSS</div>
                                <div class="flex mb-2 text-gray-700 border rounded-md px-3 py-2 bg-gray-800 text-main">GraphQL</div>
                            </div>
                        </div>
                    </div>
                    <div
                        class=" mt-5 bg-opacity-50 border border-gray-100 rounded shadow-lg bg-gradient-to-b from-gray-200 backdrop-blur-20 to-gray-50  ">
                        <div class="flex flex-row px-2 py-3 mx-3">
                            <div class="flex flex-col justify-center items-center w-full mt-1 mb-2">
                              <img src="~/assets/projects/unsacpourtous.webp" class="w-12 h-12" >
                              <div class="text-2xl text-gray-800 font-bold pt-1">Unsacpourtous</div>
                            </div>
                        </div>

                        <div class="flex justify-center text-sm font-medium text-gray-400">
                          <img class="shadow-2xl object-cover border-t-2 border-b-2 border-gray-800 h-72" src="~/assets/projects/bg-unsacpourtous.png">
                        </div>

                        <div class="mb-3 border-t border-gray-50 ">
                            <div class="flex flex-wrap justify-start mx-5 mt-6 text-sm font-semibold gap-2">
                                <div class="flex mb-2 text-gray-700 border rounded-md px-3 py-2 bg-gray-800 text-main">NuxtJS</div>
                                <div class="flex mb-2 text-gray-700 border rounded-md px-3 py-2 bg-gray-800 text-main">TailwindCSS</div>
                                <div class="flex mb-2 text-gray-700 border rounded-md px-3 py-2 bg-gray-800 text-main">GraphQL</div>
                            </div>
                        </div>
                    </div>
                    <div
                        class=" mt-5 bg-opacity-50 border border-gray-100 rounded shadow-lg bg-gradient-to-b from-gray-200 backdrop-blur-20 to-gray-50  ">
                        <div class="flex flex-row px-2 py-3 mx-3">
                            <div class="flex flex-col justify-center items-center w-full mt-1 mb-2">
                              <img src="~/assets/projects/alloccasions.svg" class="w-20 h-32 -mt-10" >
                              <div class="text-2xl text-gray-800 font-bold -mt-9">Alloccasions</div>
                            </div>
                        </div>

                        <div class="flex justify-center text-sm font-medium text-gray-400">
                            <img class="shadow-2xl object-cover border-t-2 border-b-2 border-gray-800 h-72" src="~/assets/projects/bg-alloccasions.png">
                        </div>

                        <div class="mb-3 border-t border-gray-50 ">
                            <div class="flex flex-wrap justify-start mx-5 mt-6 text-sm font-semibold gap-2">
                                <div class="flex mb-2 text-gray-700 border rounded-md px-3 py-2 bg-gray-800 text-main">NuxtJS</div>
                                <div class="flex mb-2 text-gray-700 border rounded-md px-3 py-2 bg-gray-800 text-main">TailwindCSS</div>
                                <div class="flex mb-2 text-gray-700 border rounded-md px-3 py-2 bg-gray-800 text-main">GraphQL</div>
                            </div>
                        </div>
                    </div>
                    <div
                        class=" mt-5 bg-opacity-50 border border-gray-100 rounded shadow-lg bg-gradient-to-b from-gray-200 backdrop-blur-20 to-gray-50  ">
                        <div class="flex flex-row px-2 py-3 mx-3">
                            <div class="flex flex-col justify-center items-center w-full mt-1 mb-2">
                              <img src="~/assets/projects/troi.png" class="w-10 h-12" >
                              <div class="text-2xl text-gray-800 font-bold pt-1">Troi</div>
                            </div>
                        </div>

                        <div class="flex justify-center text-sm font-medium text-gray-400">
                            <img class="shadow-2xl object-cover border-t-2 border-b-2 border-gray-800 h-72" src="~/assets/projects/bg-troi.png">
                        </div>

                        <div class="mb-3 border-t border-gray-50 ">
                            <div class="flex flex-wrap justify-start mx-5 mt-6 text-sm font-semibold gap-2">
                                <div class="flex mb-2 text-gray-700 border rounded-md px-3 py-2 bg-gray-800 text-main">NuxtJS</div>
                                <div class="flex mb-2 text-gray-700 border rounded-md px-3 py-2 bg-gray-800 text-main">TailwindCSS</div>
                                <div class="flex mb-2 text-gray-700 border rounded-md px-3 py-2 bg-gray-800 text-main">GraphQL</div>
                            </div>
                        </div>
                    </div>
                  </div>
                </div>
              </div>
            </section>
          </div>
          <div>
            <section class="py-20 bg-bubble bg-gray-100">
              <div class="container mx-auto flex flex-col items-center justify-center p-4 md:p-10">
                <div class="police text-green-400 text-5xl font-semibold">Are you</div>
                <h1 class="text-5xl font-bold leading-none text-center">Interested in my profile ?</h1>
                <div class="bg-gray-900 h-2 w-32 mt-8"></div>
                <div class="text-2xl pt-20">
                  <a href="" class="relative px-6 py-3 font-bold text-green-500 group">
                    <span class="absolute inset-0 w-full h-full transition duration-300 ease-out transform -translate-x-2 -translate-y-2 bg-gray-300 group-hover:translate-x-0 group-hover:translate-y-0"></span>
                    <span class="absolute inset-0 w-full h-full border-4 border-green-500"></span>
                    <span class="relative uppercase">Contact Me</span>
                  </a>
                </div>
              </div>
            </section>
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
.bg-bubble {
  background-image: url("~/assets/bubble.png");
  background-repeat: no-repeat;
}

</style>