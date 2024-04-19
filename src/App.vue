<script setup lang="ts"></script>

<template>
  <main class="py-6 px-4 sm:p-6 md:py-10 md:px-8">
    <div
      class="max-w-4xl mx-auto grid grid-cols-1 lg:max-w-5xl lg:gap-x-20 lg:grid-cols-2"
    >
      <div
        class="relative p-3 col-start-1 row-start-1 flex flex-col-reverse rounded-lg bg-gradient-to-t from-black/75 via-black/0 sm:bg-none sm:row-start-2 sm:p-0 lg:row-start-1"
      >
        <h1
          class="mt-1 text-lg font-semibold text-white sm:text-slate-900 md:text-2xl dark:sm:text-white"
        >
          Nur Naqiah
        </h1>
        <p
          class="text-sm leading-4 font-medium text-white sm:text-slate-500 dark:sm:text-slate-400"
        >
          22ftt1495
        </p>
      </div>
      <div
        class="grid gap-4 col-start-1 col-end-3 row-start-1 sm:mb-6 sm:grid-cols-4 lg:gap-6 lg:col-start-2 lg:row-end-6 lg:row-span-6 lg:mb-0"
      >
        <img
          src="./assets/naqiah.jpg"
          alt=""
          class="w-full h-60 object-cover rounded-lg sm:h-52 sm:col-span-2 lg:col-span-full"
          loading="lazy"
        />
        <img
          src="./assets/naqiah.jpg"
          alt=""
          class="hidden w-full h-52 object-cover rounded-lg sm:block sm:col-span-2 md:col-span-1 lg:row-start-2 lg:col-span-2 lg:h-32"
          loading="lazy"
        />
        <img
          src="./assets/naqiah.jpg"
          alt=""
          class="hidden w-full h-52 object-cover rounded-lg md:block lg:row-start-2 lg:col-span-2 lg:h-32"
          loading="lazy"
        />
      </div>
      <dl
        class="mt-4 text-xs font-medium flex items-center row-start-2 sm:mt-1 sm:row-start-3 md:mt-2.5 lg:row-start-2"
      >
        <dt class="sr-only">Contact</dt>
        <dd class="text-pink-600 flex items-center dark:text-pink-400">
          <span
            >+673 711 1111 <span class="text-slate-400 font-normal"></span
          ></span>
        </dd>
        <dt class="sr-only">Email</dt>
        <dd class="flex items-center">
          <svg
            width="2"
            height="2"
            aria-hidden="true"
            fill="currentColor"
            class="mx-3 text-slate-300"
          >
            <circle cx="1" cy="1" r="1" />
          </svg>
          example@gmail.com
        </dd>
      </dl>
      <div
        class="mt-4 col-start-1 row-start-3 self-center sm:mt-0 sm:col-start-2 sm:row-start-2 sm:row-span-2 lg:mt-6 lg:col-start-1 lg:row-start-3 lg:row-end-4"
      >
        <h2
          class="bg-pink-600 text-white text-sm leading-6 font-medium py-2 px-3 rounded-lg"
        >
          Diploma level 5 in Web Development
        </h2>
      </div>
      <div
        class="mt-4 text-sm leading-6 col-start-1 sm:col-span-2 lg:mt-6 lg:row-start-4 lg:col-span-1 dark:text-slate-400"
      >
        <h2>STUDYING:</h2>
        <p>AWEP, MWE, IPI, PMGT, WADT</p>
        <br />
        <h2>HOBBIES:</h2>
        <p>
          Watching kdrama, Listening to podcast, Playing game & Reading books
        </p>
      </div>
    </div>
  </main>
</template>

<style scoped></style>
