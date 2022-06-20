<template>
  <body>
      <navbar />
        <Disclaimer />
      <Footer />
  </body>
</template>

<script>

export default {
    name: "Communication-DisclaimerPage",
    data() {
      return {
        title: "Communication Disclaimer - Sryden",
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