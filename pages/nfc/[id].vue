<template>
  <main>
    <div>Redirecting</div>
  </main>
</template>

<script>
export default {
  props: {
    id: {
      type: String,
      default: 'alexrazbakov',
    },
  },
  mounted() {
    this.$router.push(`/${this.id}`)
  },
}
</script>
