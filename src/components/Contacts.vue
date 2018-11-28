<template>
  <div>
    <h1>{{ msg }}</h1>
    <ul>
        <li><a href="https://www.linkedin.com/in/justina-de%C5%A1ri%C5%ABt%C4%97-966153101/">linkedin</a></li>
        <li><a href="https://github.com/justinadesriuteRE">github</a></li>
        <li><a href="mailto:justina.d.lt@gmail.com">justina.d.lt@gmail.com</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Contacts',
  props: {
    msg: String
  }
}
</script>

<style>
    ul {
        list-style-type: none;
    }

    h1 {
        padding-left: 40px;
    }
</style>
