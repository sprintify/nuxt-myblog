<template>
  <div class="container font-sans text-black">
    <main-navigation></main-navigation>

    <nuxt />
  </div>
</template>

<script>
import MainNavigation from '../components/MainNavigation'
export default {
  components: {
    MainNavigation
  }
}
</script>