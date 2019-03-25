<template>
  <div class="col-12">
    <h1>Shop <span class="name">{{ name }}</span>.</h1>
    <p><nuxt-link to="/" class="button--grey">Back home</nuxt-link></p>
    <div class="row">
      <card v-for="i in 6"/>
    </div>
  </div>
</template>

<script>
import Card from '~/components/Card.vue'
export default {
  asyncData() {
    return {
      name: "Yari Yuri"
    }
  },
  components: {
    Card
  }
}
</script>

<style scoped>

</style>
