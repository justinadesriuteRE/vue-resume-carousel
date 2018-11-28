<template>
  <div>
    <h1>{{ msg }}</h1>
    <img class="edu_image" alt="Education list" src="../assets/resume_parts/education.png">
  </div>
</template>

<script>
export default {
  name: 'EduList',
  props: {
    msg: String
  }
}
</script>

<style>
    .edu_image {
        width: 20em;
        border-radius: 5px;
        padding-left: 40px;
    }
</style>
