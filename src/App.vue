<template>
  <v-app >
    <NewPostBar />
    <UsualPost />
  </v-app>
</template>

<script>
import NewPostBar from './components/NewPostBar.vue'
import UsualPost from './components/UsualPost.vue';

export default {
  name: 'App',
  components: {
    UsualPost,NewPostBar
  },
  data: () => ({
    foo:true,
    tabs:["All","Posts","Seminars","Courses","Projects"],
    settingsTabs:["Profile","Security","FAQ","Contact Us"]
  }),
};
</script>
