<template>
  <v-app>
    <Page />
    <PageTwo/>
    <PageThree/>
  </v-app>
</template>

<script>
import { defineComponent } from 'vue'

// Components
import Page from '../components/Page.vue';
import PageTwo from '../components/PageTwo.vue';
import PageThree from '../components/PageThree.vue'
export default defineComponent({
  name: 'HomeView',

  components: {
    Page,
    PageTwo,
    PageThree
}
})
</script>
<style scoped>
.v-container{
width: 1200px;
height: 700px;
border: 2px solid black;
}
.body{
  background: rgb(107, 76, 139);
}

</style>