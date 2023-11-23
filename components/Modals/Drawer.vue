<template>
  <div>
    <transition name="slide-fade">
      <div @click="emitCloseDialogEvent()" v-show="openDialog" class="h-screen cursor-pointer filter w-full bg-black bg-opacity-50 backdrop-blur-sm fixed z-30 inset-0">
      </div>
    </transition>
    
    <transition name="slide-in-left">
      <div v-show="openDialog" class="fixed w-4/5 md:w-1/2 lg:w-1/3 2xl:w-1/4 right-0 bg-white h-full z-40 top-0">
        <ul class="relative h-full flex flex-col justify-center gap-8 px-6">
          <li class="block w-full">
            <NuxtLink to="/" class="text-xl font-medium hover:text-purple-500 hover:pl-4 ease-in-out duration-300 w-full block border-b w-full pb-1 border-gray-300 hover:border-purple-500">Home</NuxtLink>
          </li>
          <li class="block w-full">
            <NuxtLink to="/" class="text-xl font-medium hover:text-purple-500 hover:pl-4 ease-in-out duration-300 w-full block border-b w-full pb-1 border-gray-300 hover:border-purple-500">About Us</NuxtLink>
          </li>
          <li class="block w-full">
            <NuxtLink to="/" class="text-xl font-medium hover:text-purple-500 hover:pl-4 ease-in-out duration-300 w-full block border-b w-full pb-1 border-gray-300 hover:border-purple-500">Roadmap</NuxtLink>
          </li>
          <li class="block w-full">
            <NuxtLink to="/" class="text-xl font-medium hover:text-purple-500 hover:pl-4 ease-in-out duration-300 w-full block border-b w-full pb-1 border-gray-300 hover:border-purple-500">Tokenomics</NuxtLink>
          </li>
          <li class="block w-full">
            <NuxtLink to="/" class="text-xl font-medium hover:text-purple-500 hover:pl-4 ease-in-out duration-300 w-full flex gap-2 hover:gap-4 items-center border-b w-full pb-1 border-gray-300 hover:border-purple-500">Join Project 
              <UiIconsUplink class="w-7 h-7" ></UiIconsUplink>
            </NuxtLink>
          </li>
        </ul>
      </div>
    </transition>
    
  </div>
</template>

<script>
export default {
  name: "Side",
  props: {
    openDialog: Boolean,
  },

  methods: {
    emitCloseDialogEvent(){
      this.$emit('closeDialog')
    }
  }

}
</script>
