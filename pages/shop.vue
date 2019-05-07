<template>
  <div class="col-12">
    <h1>Shop</h1>
    <div class="row">
      <card v-for="i in 6" key="i"/>
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
