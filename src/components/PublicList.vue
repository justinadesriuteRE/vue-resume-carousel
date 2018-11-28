<template>
  <div>
    <h1>{{ msg }}</h1>
    <img class="public_image" alt="Publications list" src="../assets/resume_parts/publications.png">
  </div>
</template>

<script>
export default {
  name: 'PublicList',
  props: {
    msg: String
  }
}
</script>   

<style>
    .public_image {
        width: 40em;
        border-radius: 5px;
        padding-left: 40px;
    }
</style>
