<template>
  <div class="">
    <header>
      <nuxt-link to="/" class="logo">
        Nuxty
      </nuxt-link>
      <nav>
        <ul>
          <li><nuxt-link to="/">Home</nuxt-link></li>
          <li><nuxt-link to="user">user</nuxt-link></li>
          <li><nuxt-link to="services">services</nuxt-link></li>
          <li><nuxt-link to="contact">contact</nuxt-link></li>
        </ul>
      </nav>
    </header>
  </div>
</template>

<script type="text/ecmascript-6">
export default {
  data() {
    return {}
  }
}
</script>

<style>
  header {
    background-color: rgb(0, 219, 146);
    display: grid;
    grid-template-colums: repeat(2, auto);
  }
</style>
