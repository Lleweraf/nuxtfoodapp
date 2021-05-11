<template>
  <footer>© {{ getYear() }} All rights reserved.</footer>
</template>

<script>
export default {
  data() {
    return {
      year: '',
    }
  },
  methods: {
    getYear() {
      const d = new Date()
      return (this.year = d.getFullYear())
    },
  },
}
</script>

<style lang="scss" scoped>
</style>