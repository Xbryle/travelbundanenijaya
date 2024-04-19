<template>
  <v-app style="background-color: transparent;">
    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>

<style>

html {
  scroll-behavior: smooth;
}

</style>
