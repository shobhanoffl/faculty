<template>
  <v-app >
      <!-- <NavBar style="position:fixed;"/> -->
      <!-- <br><br> -->
      <!-- <Profile /> -->
      <!-- <NavTab v-bind:tablist=tabs /> -->
      <!-- <UsualPost /> -->
      <!-- <UsualPost /> -->
      <!-- <NavTab v-bind:tablist=settingsTabs /> -->
      <!-- <EditProfile /> -->
      <!-- <SettingsElement /> -->
      <!-- <ContactUs /> -->
      <!-- <NewPostBar /> -->
      <!-- <NewPostBar /> -->
      <UsualPost />
  </v-app>
</template>

<script>
// import NavBar from './components/NavBar';
// import Profile from './views/Profile';
// import NavTab from './components/NavTab';
// import EditProfile from './components/EditProfile'
//  import UsualPost from './components/UsualPost';
// import SettingsElement from './components/SettingsElement'
// import ContactUs from './components/ContactUs'
// import NewPostBar from './components/NewPostBar'
// import NewPostBar from '/fac/faculty/src/components/NewPostBar'
import UsualPost from '/fac/faculty/src/components/UsualPost.vue';

export default {
  name: 'App',
  components: {
    // UsualPost,SettingsElement,EditProfile,NavTab,ContactUs,Profile,NavBar,NewPostBar
    UsualPost
  },
  data: () => ({
    foo:true,
    tabs:["All","Posts","Seminars","Courses","Projects"],
    settingsTabs:["Profile","Security","FAQ","Contact Us"]
  }),
};
</script>
