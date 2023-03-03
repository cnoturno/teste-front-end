<template>
  <div>
    <NavegationBar />
    <MainBody />
  </div>
</template>

<script>
import NavegationBar from './components/NavegationBar.vue';
import MainBody from './components/MainBody.vue';

export default {
  name: 'App',
  components: {
    NavegationBar,
    MainBody
  }
}
</script>

<style>

</style>
