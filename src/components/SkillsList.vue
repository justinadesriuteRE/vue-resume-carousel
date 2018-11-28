<template>
  <div>
    <h1>{{ msg }}</h1>
    <img class="skills_image" alt="Skills list" src="../assets/resume_parts/skills.png">
  </div>
</template>

<script>
export default {
  name: 'SkillsList',
  props: {
    msg: String
  }
}
</script>   

<style>
    .skills_image {
        width: 13em;
        border-radius: 5px;
        padding-left: 40px;
    }
</style>
