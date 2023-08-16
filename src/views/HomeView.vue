<template>
  <v-app>
    <Page />
    <PageTwo/>
    <PageThree/>
    <PageFor />
  </v-app>
</template>

<script>
import { defineComponent } from 'vue'

// Components
import Page from '../components/Page.vue';
import PageTwo from '../components/PageTwo.vue';
import PageThree from '../components/PageThree.vue'
import PageFor from '../components/PageFor.vue';
export default defineComponent({
  name: 'HomeView',

  components: {
    Page,
    PageTwo,
    PageThree,
    PageFor
   
}
})
</script>
<style>
.v-container{
width: 1200px;
height: 700px;
border: 2px solid black;
}
body{
  background: rgba(255, 249, 234, 1);
}
</style>