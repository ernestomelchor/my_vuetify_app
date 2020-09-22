<template>
  <v-app>
    <ProfilePic />
    <LinkTreeButtons />
    <MyFooter />
  </v-app>
</template>

<script>
import ProfilePic from './components/ProfilePic';
import LinkTreeButtons from './components/LinkTreeButtons';
import MyFooter from './components/MyFooter';

export default {
  name: 'App',

  components: {
    ProfilePic,
    LinkTreeButtons,
    MyFooter,
  },

  data: () => ({
    //
  }),
};
</script>
