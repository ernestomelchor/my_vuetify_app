<template>
  <v-app>
    <!-- <AppBar/> -->
    <ProfilePic />
    <LinkTreeButtons />
    <MyFooter />
  </v-app>
</template>

<script>
// import AppBar from './components/AppBar';
import ProfilePic from "./components/ProfilePic";
import LinkTreeButtons from "./components/LinkTreeButtons";
import MyFooter from "./components/MyFooter";

export default {
  name: "App",

  components: {
    // AppBar,
    ProfilePic,
    LinkTreeButtons,
    MyFooter,
  },

  data: () => ({
    //
  }),
};
</script>
