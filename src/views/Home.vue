<template>
  <q-page class="flex flex-center">
    <router-link :to="{name: 'about'}">
      about
    </router-link>
    <img
      alt="Quasar logo"
      src="../assets/logo.png"
    >
    <rx-example />
  </q-page>
</template>

<style>
</style>

<script>
import RxExample from '../components/RxExample.vue';

export default {
  name: 'PageHome',
  components: { RxExample },
};
</script>
