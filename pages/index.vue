<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        index.vueのh1要素
      </h1>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style scoped>

</style>
