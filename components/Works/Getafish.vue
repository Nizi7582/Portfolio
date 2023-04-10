<template>
  <div>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
    />
    <div>
      <div class="pt-32 flex items-center overflow-hidden relative">
        <div
          class="bg-gray-100 border-8 border-blue-300 flex-1 min-h-full min-w-full animate__animated animate__fadeInDown rounded-3xl shadow-xl p-10 lg:p-20 text-gray-800 relative md:flex items-center text-center md:text-left"
        >
          <div class="w-full md:w-1/2">
            <div class="mb-10 text-gray-600 font-light">
              <h1
                class="font-black uppercase text-3xl lg:text-5xl text-blue-300 mb-10"
              >
                {{ title }}
              </h1>
              <p class="text-lg font-medium">{{ desc }}</p>
              <p class="text-lg font-medium">{{ timespent }}</p>
            </div>
            <div class="mb-20 md:mb-0">
              <button
                class="text-lg font-light outline-none focus:outline-none transform transition-all hover:scale-110 text-blue-300 hover:text-blue-600"
              >
                <i class="mdi mdi-arrow-left mr-2"></i>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="currentColor"
                  class="w-6 h-6"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M19.5 5.25l-7.5 7.5-7.5-7.5m15 6l-7.5 7.5-7.5-7.5"
                  />
                </svg>
              </button>
            </div>
          </div>
          <div
            class="w-full md:w-1/2 flex items-center justify-center text-center"
          >
            <img alt="dropkit" src="~/assets/projects/getafish.svg" class="w-72" />
          </div>
        </div>
        <div
          class="w-64 md:w-96 h-96 md:h-full bg-blue-200 bg-opacity-30 absolute -top-64 md:-top-96 right-20 md:right-32 rounded-full pointer-events-none -rotate-45 transform"
        ></div>
      </div>
      <div class="container pt-20 pb-8 mx-auto">
        <div class="mt-8 lg:-mx-6 lg:flex lg:items-center">
          <img
            class="object-cover w-full lg:mx-6 lg:w-1/2 rounded-xl h-72 lg:h-96"
            src="~/assets/projects/bg-getafish.png"
            alt=""
          />

          <div class="mt-6 lg:w-1/2 lg:mt-0 lg:mx-6">
            <div clas="">
              <div class="">
                <div class="police text-blue-300 text-5xl font-semibold">
                  Concept
                </div>

                <div class="pt-6 font-bold text-4xl text-gray-300 md:text-5xl">
                  Description
                </div>
                <div class="bg-blue-300 h-2 w-32 mt-8"></div>
              </div>
              <div class="pt-12">
                <div class="text-gray-300 font-semibold text-2xl">
                  GetAFish est une plateforme de vente de poissons en ligne et
                  permet aux utilisateurs d'acheter facilement les poissons de
                  leur choix.
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="container mt-4 mx-auto">
        <div class="lg:-mx-6 lg:flex lg:items-center">
          <div class="lg:w-1/2 lg:mt-0 lg:mx-6">
            <div clas="">
              <div class="">
                <div class="text-gray-300 font-semibold text-2xl space-y-2">
                  Les fonctions principales du site incluent :
                  <div class="pt-4">- La recherche de poissons par espèce</div>
                  <div>- La visualisation des détails de chaque poisson</div>
                  <div>- L'ajout de poissons au panier d'achat</div>
                  <div>- La création d'un compte utilisateur</div>
                  <div>- La gestion des commandes</div>
                  <div>- La vérification des paiements</div>
                </div>
              </div>
            </div>
          </div>
          <img
            class="object-cover w-full lg:mx-6 lg:w-1/2 rounded-xl h-72 lg:h-96"
            src="~/assets/projects/bg-getafish2.png"
            alt=""
          />
        </div>
      </div>
      <div class="mb-12 pt-12 space-y-16 md:mb-20 md:pt-20 lg:mx-auto">
        <div class="mt-6 text-center mx-auto lg:mt-0 lg:mx-6">
          <div clas="">
            <div class="">
              <div class="police text-blue-300 text-5xl font-semibold">
                Infrastructure
              </div>
              <div class="pt-6 font-bold text-4xl text-gray-300 md:text-5xl">
                Front-end
              </div>
              <div class="bg-blue-300 h-2 w-32 mt-8 mx-auto"></div>
            </div>
            <div class="pt-12">
              <div class="w-full flex justify-center border-4 border-white">
                <div>
                  <img
                    src="~/assets/projects/bg-nuxt.png"
                    class="bg-gray-100 rounded-3xl"
                  />
                </div>
              </div>
              <div class="text-gray-300 font-semibold text-2xl pt-10">
                J'ai choisi d'utiliser Nuxt 2 pour plusieurs raisons.
                <div></div>
                Tout d'abord, c'est un framework JavaScript open-source basé sur
                Vue.js qui permet de créer des applications web universelles et
                des sites web statiques.
                <div></div>
                Il offre des avantages tels qu'une gestion efficace de l'état de
                l'application, un rendu côté serveur (SSR) pour une meilleure
                optimisation du référencement et une expérience utilisateur plus
                rapide et fluide.
                <div></div>
                De plus, Nuxt est facile à utiliser et à configurer.
              </div>
            </div>
          </div>
        </div>
        <div class="">
          <div class="pt-6 font-bold text-4xl text-gray-300 md:text-5xl text-center">
            Back-end
          </div>
          <div class="bg-blue-300 h-2 w-32 mt-8 mx-auto"></div>
          <div
            class="grid grid-cols-2 gap-12 pt-4"
          >
            <div class="flex flex-col items-center">
              <img
                src="~/assets/projects/php.png"
                alt="image"
                loading="lazy"
                width=""
                height=""
                class="h-52"
              />
              <div class="pt-12">
                <div class="text-gray-300 font-semibold text-2xl text-center">
                  Pour la gestion de la base de données, j'ai utilisé Php, l'un des langages de programmation les plus populaires pour la création de sites web dynamiques.<div></div> Php est facile à utiliser et possède une grande communauté de développeurs qui ont créé de nombreux outils et bibliothèques pour faciliter le développement web.
                </div>
              </div>
            </div>
            <div class="flex flex-col items-center">
              <img
                src="~/assets/projects/phpmyadmin.png"
                alt="image"
                loading="lazy"
                width=""
                height=""
                class="h-52"
              />
              <div class="pt-12">
                <div class="text-gray-300 font-semibold text-2xl text-center">
                  J'ai utilisé PhpmyAdmin pour gérer ma base de données, ce qui m'a offert une interface web conviviale pour gérer les données de mon site web. <div></div>PhpmyAdmin est un outil open-source qui permet de gérer les bases de données MySql à l'aide d'une interface utilisateur graphique.                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true,
    },
    desc: {
      type: String,
      required: true,
    },
    timespent: {
      type: String,
      required: true,
    },
    img: {
      type: String,
      required: true,
    },
  },
}
</script>
