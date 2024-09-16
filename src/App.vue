<template>
  <v-app>
    <v-main>
      <HelloWorld />
    </v-main>
  </v-app>
</template>

<script lang="ts">
  import { defineComponent } from 'vue';
  import { VApp, VMain } from 'vuetify/components';

  export default defineComponent({
    components: {
      VApp,
      VMain,
    },
  });
</script>
