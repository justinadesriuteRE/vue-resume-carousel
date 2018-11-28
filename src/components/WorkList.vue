<template>
  <div>
    <h1>{{ msg }}</h1>
    <img class="work_image" alt="Work list" src="../assets/resume_parts/work.png">
  </div>
</template>

<script>
export default {
  name: 'WorkList',
  props: {
    msg: String
  }
}
</script>

<style>
    .work_image {
        width: 40em;
        border-radius: 5px;
        padding-left: 40px;
    }
</style>
