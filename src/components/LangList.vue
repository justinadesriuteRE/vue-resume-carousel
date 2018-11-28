<template>
  <div>
    <h1>{{ msg }}</h1>
    <img class="lang_image" alt="Languages list" src="../assets/resume_parts/languages.png">
  </div>
</template>

<script>
export default {
  name: 'LangList',
  props: {
    msg: String
  }
}
</script>

<style>
    .lang_image {
        width: 15em;
        border-radius: 5px;
        padding-left: 40px;
    }
</style>
