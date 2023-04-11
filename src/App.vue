<template>
    <div>
        <show-blogs></show-blogs>
        <list-blogs></list-blogs>
    </div>
</template>

<script>
// Imports
import showBlogs from './components/showBlogs.vue';
import listBlogs from './components/listBlogs.vue';

export default {
    components: {
        'show-blogs': showBlogs,
        'list-blogs': listBlogs
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
