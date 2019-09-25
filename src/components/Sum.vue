<template>
  <div class="sum">
    {{ sum }}
  </div>
</template>

<script>
export default {
  name: 'Sum',
  computed: {
    sum() {
      return this.$store.getters.sum
    },
    numbers(){
      return this.$store.getters.numbers
    }
  },
}
</script>
