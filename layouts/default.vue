<template>
  <div
    class="container"
    style="max-width: 375px; margin: 0 auto; border: 1px solid gray;"
  >
    <Nav />
    <nuxt />
  </div>
</template>

<script>
import Nav from './partials/nav.vue'
export default {
  components: {
    Nav
  }
}
</script>
