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
      const file = 'ocaminhodaservidao.pdf' // 将'your-file-name'替换为实际的文件名
      window.open(`/${file}`, '_self')
    }
  }
}
</script>
