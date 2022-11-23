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
          <Home />
          <Biography />
          <Skills />
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
                        <div class="flex flex-wrap group cursor-pointer" @click="kity = true">
                            <div class="w-full p-1 md:p-2 relative">
                                <img alt="gallery" class="block object-cover object-center w-full h-full rounded-lg transition duration-300 group-hover:opacity-80" src="~/assets/kity/kity8.jpg">
                                <div class="absolute top-4 left-6 opacity-0 group-hover:opacity-100 transition police text-gray-800 text-4xl font-semibold">My Cat</div>                              
                            </div>
                        </div>
                        <div class="flex flex-wrap group cursor-pointer" @click="voyage = true">
                            <div class="w-full p-1 md:p-2 relative">
                              <img alt="gallery" class="block object-cover object-center w-full h-full rounded-lg transition duration-300 group-hover:opacity-80" src="~/assets/voyages/states.jpg">
                                <div class="absolute top-4 left-6 opacity-0 group-hover:opacity-100 transition police text-gray-800 text-4xl font-semibold">My Travels</div> 
                            </div>
                        </div>
                        <div class="flex flex-wrap group cursor-pointer">
                            <div class="w-full p-1 md:p-2 relative">
                                <img alt="gallery" class="block object-cover object-center w-full h-full rounded-lg transition duration-300 group-hover:opacity-80"
                                src="https://mdbcdn.b-cdn.net/img/Photos/Horizontal/Nature/4-col/img%20(75).webp">
                                <div class="absolute top-4 left-6 opacity-0 group-hover:opacity-100 transition police text-gray-800 text-4xl font-semibold">My Hobbies</div> 
                            </div>
                        </div>
                    </div>
                    </div>
                </section>
                </div>
            </div>
          </div>
          <Projects />
          <Contact />
        </div>
      </div>
    </div>
    <GalleryKitty v-if="kity" @close="kity = false" />
    <GalleryVoyages v-if="voyage" @close="voyage = false" />
  </div>
</template>

<script>
export default {
  data() {
    return {
      kity: false,
      voyage: false
    }
  }
}
</script>

<style>
.bg-bubble {
  background-image: url("~/assets/bubble.png");
  background-repeat: no-repeat;
}
.grow { transition: all .2s ease-in-out; }
.grow:hover { transform: scale(0.8); }

.hover01 img {
	-webkit-transform: scale(1);
	transform: scale(1);
	-webkit-transition: .3s ease-in-out;
	transition: .3s ease-in-out;
}
.hover01:hover img {
	-webkit-transform: scale(1.3);
	transform: scale(1.3);
}
</style>