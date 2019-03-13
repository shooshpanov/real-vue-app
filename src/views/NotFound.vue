<template>
  <div>
    <h1>Ooops!</h1>
    <h3>The {{ resource }} page you're loking for is not found here.</h3>
    <router-link :to="{ name: 'event-list' }">
      Back to the Home page</router-link
    >
  </div>
</template>

<script>
export default {
  props: {
    resource: {
      type: String,
      required: true
    }
  }
}
</script>

<style scoped></style>
