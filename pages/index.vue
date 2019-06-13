<template>
  <div>
    <navbar />
    <div class="container">
      <div>
        <logo />
        <h1 class="title">
          index.vueのh1要素
        </h1>
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue'
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Navbar,
    Logo
  }
}
</script>

<style scoped>

</style>
