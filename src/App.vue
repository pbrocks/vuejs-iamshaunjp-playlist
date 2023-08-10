<template>
    <div>
        <app-header :title="title"></app-header>
        <p>App.vue:4</p>
        <app-ninjas :ninjas="ninjas"></app-ninjas>
        <p>App.vue:6</p>
        <ul>
          <li v-for="ninja in ninjas">{{ ninja.name }}</li>
        </ul>
        <p>App.vue:10</p>
        <app-footer :title="title"></app-footer>
    </div>
</template>

<script>
// Imports
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
import Ninjas from './components/Ninjas.vue';

export default {
    components: {
        'app-header': Header,
        'app-footer': Footer,
        'app-ninjas': Ninjas
    },
    data () {
        return {
          ninjas: [
              {name: 'Ryu', speciality: 'Vue Components', show: false},
              {name: 'Crystal', speciality: 'HTML Wizardry', show: false},
              {name: 'Hitoshi', speciality: 'Click Events', show: false},
              {name: 'Tango', speciality: 'Conditionals', show: false},
              {name: 'Kami', speciality: 'Webpack', show: false},
              {name: 'Yoshi', speciality: 'Data Diggin', show: false}
          ],
          title: 'Vue Wizards'
        }
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
