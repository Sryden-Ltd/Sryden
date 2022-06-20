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
        title: "HomePage - Sryden",
      }
    },
    head() {
      return {
        title: this.title,
        meta: [
          {
            hid: "description",
            name: "description",
            content: "Sryden is an independent development studio based out of Scotland, creating software solutions for one of the UK's largest industrial sectors: Web hosting companies.",
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
