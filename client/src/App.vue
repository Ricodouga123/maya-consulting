<template>
  <v-app>
    <v-app-bar app color="primary" dark class="d-flex align-center">
      <div>
        <v-img
          class="shrink mr-2"
          contain
          :src="require('@/assets/png/logo-no-background.png')"
          transition="scale-transition"
          width="120"
          height="50"
        />
      </div>

      <v-btn class="mr-3" color="accent">
        About Us
      </v-btn>

      <v-btn class="mr-3" color="accent">
        What We Do
      </v-btn>

      <v-btn class="mr-3" color="accent">
        Contact Us
      </v-btn>
    </v-app-bar>

    <v-main>
      <HelloWorld/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
