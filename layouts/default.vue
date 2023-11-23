<template>
  <nav class="flex items-center justify-between py-5 px-6 md:px-8 lg:px-10 xl:px-16 relative">
    <NuxtLink to="/" class="wakanda font-bold text-2xl">Wakanda<br />Currency</NuxtLink>
    <button class="z-50 bg-purple-700 hover:bg-purple-500 duration-300 ease-in-out rounded-full h-16 aspect-square grid place-items-center fixed right-6 md:right-8 lg:right-10 xl:right-16 shadw border-2 border-white">
      <UiButtonsMenu @revealMenu="toggleMenu"/>
    </button>
  </nav>
  <main>
    <slot />
  </main>
  <NavigationFooter />
  <ModalsDrawer :openDialog="Menu" />
</template>
<script>
export default {
  data(){
    return {
      Menu: false,
    }
  },

  methods: {
    toggleMenu() {
      this.Menu = !this.Menu
    }
  }
}
</script>
<style>
.shadw {
  box-shadow: 0 25px 50px -12px rgb(0 0 0 / 0.75);
}
</style>