<!-- This is for group component member -->

<template>
  <div class="flex flex-col items-center gap-4">
    <div class="text-center">
      <h1 class="text-xl lg:text-4xl font-extrabold">
        {{ props.groupName }}
      </h1>
      <p>
        {{ props.description }}
      </p>
    </div>
    <div class="my-8">
      <NuxtLink :to="props.memberUrl" :class="props.color" class="  p-4  hover:opacity-110
         transition duration-150 ease-in-out ">See Member</NuxtLink>
    </div>
    <!-- <div class="">
      <img class="w-34" :src="$props.groupImg" :alt="$props.groupName" />
    </div> -->
  </div>
</template>

<script setup lang="ts">
const props = defineProps({
  groupName: String,
  description: String,
  groupImg: String,
  memberUrl: String,
  color: String
})
</script>