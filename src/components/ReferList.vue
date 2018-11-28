<template>
  <div>
    <h1>{{ msg }}</h1>
    <img class="refer_image" alt="References list" src="../assets/resume_parts/references.png">
  </div>
</template>

<script>
export default {
  name: 'ReferList',
  props: {
    msg: String
  }
}
</script>   

<style>
    .refer_image {
        width: 45em;
        border-radius: 5px;
        padding-left: 40px;
    }
</style>
