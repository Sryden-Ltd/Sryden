<template>
  <body>
      <navbar />
        <ImprintHero />
      <Footer />
  </body>
</template>

<script>

export default {
    name: "ImprintPage",
    data() {
      return {
        title: "Sryden - Imprint",
      }
    },
    head() {
      return {
        title: this.title,
        meta: [
          {
            hid: "description",
            name: "description",
            content: "Sryden - Imprint",
          },
        ],
      }
    }
}
</script>

<style>
  html {
    scroll-behavior: smooth;
  }
</style>