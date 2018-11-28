<template>
  <div id="app">
    <carousel :per-page="1" :mouse-drag="true" :autoplay="false" :autoplayHoverPause="false"
    :paginationSize="14">
      <slide data-index="0"
          data-name="MySlideName"
          v-on:click="handleSlideClick">
        <BasicList msg="Basics"/>
      </slide>
      <slide data-index="1"
          data-name="MySlideName"
          v-on:click="handleSlideClick">
        <WorkList msg="Experience"/>
      </slide>
      <slide data-index="2"
          data-name="MySlideName"
          v-on:click="handleSlideClick">
        <EduList msg="Education"/>
      </slide>
      <slide data-index="3"
          data-name="MySlideName"
          v-on:click="handleSlideClick">
        <InterestsList msg="Interests"/>
      </slide>
      <slide data-index="4"
          data-name="MySecondSlideName"
          v-on:click="handleSlideClick">
          <LangList msg="Languages"/>
      </slide>
      <slide data-index="5"
          data-name="MySecondSlideName"
          v-on:click="handleSlideClick">
          <PublicList msg="Publications"/>
      </slide>
      <slide data-index="6"
          data-name="MySecondSlideName"
          v-on:click="handleSlideClick">
          <ReferList msg="References"/>
      </slide>
      <slide data-index="7"
          data-name="MySecondSlideName"
          v-on:click="handleSlideClick">
          <SkillsList msg="Skills"/>
      </slide>
      <slide data-index="8"
          data-name="MySecondSlideName"
          v-on:click="handleSlideClick">
          <VolunteerList msg="Volunteering"/>
      </slide>
    </carousel>
  </div>
</template>

<script>

import { Carousel, Slide } from 'vue-carousel'
import BasicList from './components/BasicList.vue'
import WorkList from './components/WorkList.vue'
import EduList from './components/EduList.vue'
import InterestsList from './components/InterestsList.vue'
import LangList from './components/LangList.vue'
import PublicList from './components/PublicList.vue'
import ReferList from './components/ReferList.vue'
import SkillsList from './components/SkillsList.vue'
import VolunteerList from './components/VolunteerList.vue'

export default {
  name: 'app',
  components: {
    Carousel,
    Slide,
    BasicList,
    WorkList,
    EduList,
    InterestsList,
    LangList,
    PublicList,
    ReferList,
    SkillsList,
    VolunteerList
  }, 
  methods: {
    handleSlideClick: function () {
      console.log('click')
    }
  }
}

</script>

<style>

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>
