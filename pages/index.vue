<template>
  <div class="container">
    <h1>Hello</h1>
    <input type="text" v-model="text" />
    <p>{{ text }}</p>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue';

export default {
  data() {
    return {
      text: '',
    };
  },
};
</script>

<style>
input {
  display: block;
}
</style>
