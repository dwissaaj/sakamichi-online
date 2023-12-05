<template>
  <div class="max-w-full ">
    <div class="flex justify-center  gap-3
   lg:gap-8 font-inter text-xl ">
      <NuxtLink class="text-black/50 transition duration-150 ease-out hover:text-teal-500" href="/">Home</NuxtLink>
      <NuxtLink class="text-black/50 transition duration-150 ease-out hover:text-teal-500" href="members">Member
      </NuxtLink>
    </div>
    <div class="font-inter">
      <slot />
    </div>
    <div class="m-8 flex flex-col lg:flex-row justify-center gap-8">
      <div class="">
        <NuxtLink class="flex gap-8 justify-center items-center text-black/80 hover:text-teal-500"  to="https://www.nogizaka46.com/">
        
          <img src="/logo/nogizaka.png" alt="nogizaka46" />
          <p>Official Website Nogizaka46</p>
        </NuxtLink>
      
      </div>
      <div class="">
        <NuxtLink class="flex gap-8 justify-center items-center text-black/80 hover:text-teal-500"  to="https://sakurazaka46.com/">
      
          <img src="/logo/sakura.png" alt="nogizaka46" />
          <p>Official Website Sakurazaka46</p>
        </NuxtLink>
      
      </div>
      <div class="">
        <NuxtLink class="flex gap-8 justify-center items-center text-black/80 hover:text-teal-500"  to="http://stage48.net/wiki/index.php/Hinatazaka46">
        
          <img src="/logo/hinata.png" alt="nogizaka46" />
          <p>Official Website Hinatazaka46</p>
        </NuxtLink>
      
      </div>
    </div>
  </div>
</template>