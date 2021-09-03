<template>
  <v-app>
     <v-content>
      <MemoAppComp/>
    </v-content>
  </v-app>
</template>

<script>
import MemoAppComp from './components/MemoApp';

export default {
  name: 'App',

  components: {
    MemoAppComp,
  },

  data: () => ({
    //
  }),
};
</script>