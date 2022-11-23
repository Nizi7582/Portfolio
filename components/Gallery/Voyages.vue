<template>
    <div
    class="fixed z-20 inset-0 overflow-y-auto transition"
    aria-labelledby="modal-title"
    role="dialog"
    aria-modal="true"
  >
    <div
      class="flex items-end justify-center min-h-screen px-4 text-center sm:block sm:p-0"
    >
      <div
        :class="{ 'opacity-0': !open, 'opacity-100': open }"
        class="ease-out duration-300 fixed inset-0 bg-gray-500 bg-opacity-75 transition-opacity"
        aria-hidden="true"
      />
      <span
        class="hidden sm:inline-block sm:align-middle sm:h-screen"
        aria-hidden="true"
        @click="Close"
      ></span>
      <div
        :class="{
          'opacity-0 translate-y-4 sm:translate-y-0 sm:scale-75': !open,
          'opacity-100 translate-y-0 sm:scale-100': open,
        }"
        class="ease-out duration-300 inline-block align-bottom bg-white rounded-lg p-2 bg-green-500 text-left overflow-hidden shadow-xl transform transition-all sm:align-middle sm:max-w-6xl w-5/6 lg:w-full"
      >
        <div>
          <button
            type="button"
            class="absolute hidden top-4 left-4 sm:flex rounded-md text-gray-400 hover:text-gray-500"
            @click="Close"
          >
            <svg
              class="h-7 w-7 text-green-500"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              aria-hidden="true"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M6 18L18 6M6 6l12 12"
              />
            </svg>
          </button>
          <div class="2xl:px-20 lg:px-12 px-4 py-8 bg-gray-800 rounded-lg">
            <div class="text-center font-bold text-5xl text-gray-900 md:text-6xl pt-4">
                <div class="police text-green-400 text-5xl font-semibold">My Travels</div>
                <div class="text-gray-300 pt-2">United States</div>
                <div class="bg-green-400 h-2 w-32 mt-8 mx-auto"></div>
            </div>
            <div class="mt-4">
                <div class="grid grid-cols-3 gap-4">
                    <img tabindex="0" src="~/assets/voyages/states2.jpg" alt="my cat picture" class="rounded-lg mb-4 object-cover object-fit" />
                    <img tabindex="0" src="~/assets/voyages/states3.jpg" alt="my cat picture" class="rounded-lg object-cover object-fit" />
                    <img tabindex="0" src="~/assets/voyages/states1.jpg" alt="my cat picture" class="rounded-lg object-cover object-fit" />
                </div>
                <div class="flex items-center justify-center my-6">
                    <img tabindex="0" src="~/assets/voyages/states4.jpg" alt="my cat picture" class="h-96 object-cover object-fit rounded-lg" />                    
                </div>
            </div>
          <!--  <div class="text-center font-bold text-5xl text-gray-900 md:text-6xl pt-4">
                <div class="text-gray-300 pt-2">Spain</div>
                <div class="bg-green-400 h-2 w-32 mt-8 mx-auto"></div>
            </div>
            <div class="mt-4">
                <div class="grid grid-cols-3 gap-4">
                    <img tabindex="0" src="~/assets/voyages/states2.jpg" alt="my cat picture" class="rounded-lg mb-4 object-cover object-fit" />
                    <img tabindex="0" src="~/assets/voyages/states3.jpg" alt="my cat picture" class="rounded-lg object-cover object-fit" />
                    <img tabindex="0" src="~/assets/voyages/states1.jpg" alt="my cat picture" class="rounded-lg object-cover object-fit" />
                </div>
                <div class="flex items-center justify-center my-6">
                    <img tabindex="0" src="~/assets/voyages/states4.jpg" alt="my cat picture" class="h-96 object-cover object-fit rounded-lg" />                    
                </div>
            </div> -->
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
      open: false,
    }
  },
  async mounted() {
    await this.sleep(100)
    this.open = true
  },
  methods: {
    // eslint-disable-next-line require-await
    async sleep(ms) {
      return new Promise((resolve) => setTimeout(resolve, ms))
    },
    async Close() {
      this.open = false
      await this.sleep(200)
      this.$emit('close', true)
    },
  },
}
</script>

<style scoped>
.bg-kity {
    background-image: url("~/assets/bubble.png");
    background-repeat: no-repeat;
}
</style>
