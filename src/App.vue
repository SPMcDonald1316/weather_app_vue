<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input type="text" class="search-bar" placeholder="Location..."/>
      </div>
    </main>
  </div>
</template>

<script>

export default {
  name: 'App',
  data() {
    return {
      apiKey: process.env.VUE_APP_KEY
    }
  }
}
</script>

<style>

</style>
