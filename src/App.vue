<template>
  <v-app>
      <NavBar style="position:fixed;"/>
      <br><br>
      <Profile />
      <!-- <NavTab v-bind:tablist=tabs /> -->
      <!-- <UsualPost /> -->
      <!-- <UsualPost /> -->
      <!-- <NavTab v-bind:tablist=settingsTabs /> -->
      <!-- <EditProfile /> -->
      <!-- <SettingsElement /> -->
      <!-- <ContactUs /> -->
  </v-app>
</template>

<script>
import NavBar from './components/NavBar';
import Profile from './views/Profile';
// import NavTab from './components/NavTab';
// import EditProfile from './components/EditProfile'
//  import UsualPost from './components/UsualPost';
// import SettingsElement from './components/SettingsElement'
// import ContactUs from './components/ContactUs'

export default {
  name: 'App',
  components: {
    // UsualPost,SettingsElement,EditProfile,SettingsElement
    // NavTab,ContactUs
    Profile,NavBar
  },
  data: () => ({
    tabs:["All","Posts","Seminars","Courses","Projects"],
    settingsTabs:["Profile","Security","FAQ","Contact Us"]
  }),
};
</script>
