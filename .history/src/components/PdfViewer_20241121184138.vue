<template>
  <div>
    
  </div>
</template>

<script>
export default {
  mounted() {
    this.openPdf()
  },
  methods: {
    openPdf() {
      const file = this.$route.params.file
      const pdfUrl = '/' + file + '.pdf'
      // window.open(pdfUrl, '_blank')
    }
  }
}
</script>
<style>
.sx-link {
  position: absolute;
  right: 10px;
  bottom: 10px;
  z-index: 1000;
}
.sx-logo {
  width: 50px;
  height: 50px;
}
</style>