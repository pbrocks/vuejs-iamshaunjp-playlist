<template>
    <div>
        <show-blogs></show-blogs>
    </div>
</template>

<script>
// Imports
import showBlogs from './components/showBlogs.vue';

export default {
    components: {
        'show-blogs': showBlogs
    },
    data () {
        return {

        }
    },
    methods: {

    }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Nunito:wght@600&display=swap');
  body{
      margin: 0;
      font-family: 'Nunito';
  }
</style>
