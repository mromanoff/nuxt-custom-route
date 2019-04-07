<template>
  <section class="container">
    <h1 class="title">This is an directory page: {{ make }}</h1>
  </section>
</template>

<script>
export default {
  data() {
    return {
      make: this.$route.path.replace(/\//g, '')
    }
  }
}
</script>
