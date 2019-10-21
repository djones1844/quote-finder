<template>
  <div class="app">
    <h1>Quote Finder</h1>
    <div class="input-group">
      <input class="form-control" type="text" id="searchInput"> 
      <div class="input-group-append" >
        <span class="input-group-text"><img class="search-solid" src="../assets/search-solid.svg"></span>
      </div>
    </div>
  </div>

</template>

<script>
export default {
  name: 'app',
  props: {}
}
</script>
<style scoped>
  .search-solid {
    height: 1.5em;
    width: 2em;
  }
  .input-group {
    width: 80%;
    margin-left: 10%;
  }
</style>
