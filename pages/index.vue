<template>
  <body>
      <navbar />
      <TitleHero />
      <Brands />
      <Footer />
  </body>
</template>

<script>
export default {
    name: "IndexPage",
    data() {
      return {
        title: "Sryden - HomePage",
      }
    },
    head() {
      return {
        title: this.title,
        meta: [
          {
            hid: "description",
            name: "description",
            content: "Sryden - HomePage",
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
