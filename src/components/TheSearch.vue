<template>
  <div class='search'>
    <form @submit.prevent='searchNickname'>
      <input type='text' placeholder='Enter the nickname of the dude that you want to search..' v-model='nickname'>
    </form>
  </div>
</template>

<script>
export default {
  'name': 'TheSearch',
  'data': function() {
    return {
      'nickname': ''
    }
  },
  'methods': {
    searchNickname() {
      console.log(this['nickname'])
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
