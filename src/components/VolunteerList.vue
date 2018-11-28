<template>
  <div>
    <h1>{{ msg }}</h1>
    <img class="volunteer_image" alt="Volunteering list" src="../assets/resume_parts/volunteer.png">
  </div>
</template>

<script>
export default {
  name: 'VolunteerList',
  props: {
    msg: String
  }
}
</script>   

<style>
    .volunteer_image {
        width: 45em;
        border-radius: 5px;
    }
</style>
