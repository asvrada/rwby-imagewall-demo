<template>
  <div id="app">
    <vue-image-wall :link-images="listImages" />
  </div>
</template>

<script>

  import VueImageWall from 'vue-image-wall';

  export default {
    name: 'App',
    components: {
      VueImageWall,
    },
    data: function () {
      return {
        listImages: [
          'rwby/ruby.jpg',
          'rwby/weiss.jpg',
          'rwby/blake.jpg',
          'rwby/yang.jpg'
        ]
      }
    }
  };
</script>

<style>
</style>
