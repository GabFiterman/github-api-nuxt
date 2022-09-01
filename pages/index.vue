<template>
  <v-container>
    <h1>Index</h1>
    <h2>{{ dot_env_test}}</h2>

  </v-container>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      dot_env_test: process.env.API_URL
    }
  }
}
</script>
