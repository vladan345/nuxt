<template>
   <header class="h-[80px] w-full bg-black px-[240px] flex justify-end">
      <nav class="text-white flex items-center h-full gap-4">
         <NuxtLink class="bg-slate-800 hover:bg-slate-600 p-3 rounded-lg" to="/"
            >Home</NuxtLink
         >
         <NuxtLink
            class="bg-slate-800 hover:bg-slate-600 p-3 rounded-lg"
            to="/about"
            >About</NuxtLink
         >
         <NuxtLink
            class="bg-slate-800 hover:bg-slate-600 p-3 rounded-lg"
            to="/contact"
            >Contact</NuxtLink
         >
      </nav>
   </header>
</template>
