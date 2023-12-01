<template>
  <div class="flex w-screen justify-center items-center gap-3
   lg:gap-8 font-inter text-xl mt-4">
    <NuxtLink 
    class="text-black/50 transition duration-150 ease-out hover:text-purple-500"
     href="/">Home</NuxtLink>
    <NuxtLink class="text-black/50 transition duration-150 ease-out hover:text-purple-500" 
    href="members">Member</NuxtLink>
  </div>
    <div class="font-inter">
      <slot />
    </div>
  </template>