<template>
    <div>
        <add-blog></add-blog>
    </div>
</template>

<script>
// Imports
import addBlog from './components/addBlog.vue';

export default {
    components: {
        'add-blog': addBlog
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
