<template>
  <v-main>
    <v-container>
      <v-responsive>
        <v-row align="center">
              <v-btn class="my-2" dark x-large block color="primary" :elevation="24"><v-icon>mdi-web</v-icon>Portfolio</v-btn>
              <v-btn class="my-2" dark x-large block color="primary" :elevation="24"><v-icon>mdi-linkedin</v-icon>LinkedIn</v-btn>
              <v-btn class="my-2" dark x-large block color="primary" :elevation="24"><v-icon>mdi-instagram</v-icon>Instagram</v-btn>
              <v-btn class="my-2" dark x-large block color="primary" :elevation="24"><v-icon>mdi-twitter</v-icon>Twitter</v-btn>
              <v-btn class="my-2" dark x-large block color="primary" :elevation="24"><v-icon>mdi-youtube</v-icon>YouTube</v-btn>
        </v-row>
      </v-responsive>
    </v-container>
  </v-main>
</template>

<script>
export default {
  name: 'LinkTreeButtons'
}
</script>

<style>

</style>