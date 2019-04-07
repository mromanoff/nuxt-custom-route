<template>
  <section class="container">
    <h1 class="title">This is an category page: {{ category }}</h1>
  </section>
</template>

<script>
export default {
  data() {
    return {
      category: this.$route.path.replace(/\//g, '')
    }
  }
}
</script>
