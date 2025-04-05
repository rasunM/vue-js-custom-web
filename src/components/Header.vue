<template>
  <header class="mx-50 mt-10">
    <div class="flex justify-between m-4">
      <!-- logo area -->
      <div class="flex text-2xl font-bold">
        <img src="/favicon.ico" />Logo.lk
      </div>
      <!-- Navigation area -->
      <nav class="flex gap-10 text-xl">
        <a href="#" class="hover:underline">Personal</a
        ><a href="#" class="hover:underline">Business</a
        ><a href="#" class="hover:underline">Partner</a
        ><a href="#" class="hover:underline">About Us</a>
      </nav>
      <button class="bg-black rounded-full px-4 py-2 text-white">
        Sign in
      </button>
    </div>
    <main class="flex mx-5 my-10 justify-between">
      <div>
        <h1 class="text-6xl font-bold mt-10 mb-10">Rasun Manohara</h1>
        <p class="w-[600px] text-xl font-medium mb-10">
          This is a simple Vue.js application that demonstrates how to use
          components, data binding, and interactivity. With Vue, you can build
          dynamic user interfaces efficiently and quickly. Enjoy exploring the
          features of this app!
        </p>
        <button
          class="text-black border border-2 border-black rounded-full px-4 py-2"
        >
          See more
        </button>
      </div>
      <div class="">
        <img src="/computer.jpg" />
      </div>
    </main>
  </header>
</template>
