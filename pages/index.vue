<template>
  <Tutorial />
</template>

<script lang="ts">
import Vue from 'vue'
Vue.extend({})

export default {
  head() {
    return {
      script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }],
    };
  },
};
</script>
