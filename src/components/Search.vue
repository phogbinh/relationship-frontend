<template>
  <div class='search'>
    <input type='text' placeholder='Enter the nickname of the dude that you want to search..' v-model='nickname'>
  </div>
</template>

<script>
export default {
  'name': 'Search',
  'data': function() {
    return {
      'nickname': ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
