<template>
  <div>
    <h1>{{ msg }}</h1>
    <img class="interests_image" alt="Interests list" src="../assets/resume_parts/interests.png">
  </div>
</template>

<script>
export default {
  name: 'InterestsList',
  props: {
    msg: String
  }
}
</script>

<style>
    .interests_image {
        width: 15em;
        border-radius: 5px;
        padding-left: 40px;
    }
</style>
