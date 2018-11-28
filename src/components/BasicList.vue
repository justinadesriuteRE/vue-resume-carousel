<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <img class="basic_image" alt="Basic information list" src="../assets/resume_parts/basic.png">
  </div>
</template>

<script>
export default {
  name: 'BasicList',
  props: {
    msg: String
  }
}
</script>

<style>

  .basic_image {
    width: 45em;
    border-radius: 5px;
  }
</style>
