<template>
    <div>
        <h1>{{ title }}</h1>
        <p>{{ greeting() }}</p>
    </div>
</template>

<script>
export default {
    data () {
        return {
          title: 'Your first Vue file, woohoo!'
        }
    },
    methods: {
        greeting: function(){
            return 'heeyaaahh cowboy'
        }
    }
}
</script>

<style>
</style>
