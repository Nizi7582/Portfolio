<template>
  <div class="max-w-7xl w-full mx-auto z-20 top-0 absolute animate__animated animate__fadeInDown">
    <div class="mx-auto py-3 px-5">
      <div class="relative flex items-center ">
        <div
          class="flex items-center justify-center sm:justify-between w-full"
        >
          <nuxt-link to="/" class="flex items-center space-x-6">
            <div class="text-xl font-bold text-gray-200 police p-2">Nizaar Znagui</div>
            <div class="text-md font-semibold text-gray-200 uppercase">Web Developper</div>
          </nuxt-link>
          <div class="hidden sm:block sm:ml-6">
              
            <div class="flex items-center justify-between space-x-8">
              
              <nuxt-link
                to="/about"
                class="text-gray-200 px-3 py-2 text-md font-medium link link-underline link-underline-black"
                aria-current="page"
                >Home</nuxt-link
              >
              <nuxt-link
                to="/works/"
                class="text-gray-200 hover:text-gray-200 px-3 py-2 text-md font-medium link link-underline link-underline-black"
                >Works</nuxt-link
              >
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Mobile menu, show/hide based on menu state. -->
    <div class="sm:hidden" id="mobile-menu">
      <div class="px-2 pt-2 pb-3 space-y-1">
        <!-- Current: "bg-gray-900 text-gray-200", Default: "text-gray-300 hover:bg-gray-700 hover:text-gray-200" -->
        <nuxt-link
          to="#"
          class="bg-gray-900 text-gray-200 block px-3 py-2 rounded-md text-base font-medium"
          aria-current="page"
          >Home</nuxt-link
        >

        <nuxt-link
          to="#"
          class="text-gray-300 hover:bg-gray-700 hover:text-gray-200 block px-3 py-2 rounded-md text-base font-medium"
          >Works</nuxt-link
        >

      </div>
    </div>
  </div>
</template>

<style>
.link-underline {
  border-bottom-width: 0;
  background-image: linear-gradient(transparent, transparent),
    linear-gradient(#fff, #fff);
  background-size: 0 3px;
  background-position: 0 100%;
  background-repeat: no-repeat;
  transition: background-size 0.3s ease-in-out;
}

.link-underline-black {
  background-image: linear-gradient(transparent, transparent),
    linear-gradient(rgba(222, 255, 34, 0.9), rgba(159, 255, 34, 0.916));
}

.link-underline:hover {
  background-size: 100% 3px;
  background-position: 0 100%;
}
.police {
  font-family: 'Segoe Print'
}
.blur {
  -webkit-backdrop-filter: blur(8px);
  backdrop-filter: blur(8px);
}
</style>
