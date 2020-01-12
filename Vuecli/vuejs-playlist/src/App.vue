<template>
  <div>
    <app-header></app-header>
    <app-ninja></app-ninja>
    <app-footer></app-footer>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import Ninja from './components/Ninjas.vue'

export default {
components:{
  'app-header':Header,
  'app-footer':Footer,
  'app-ninja':Ninja
},
    data() {
        return {
        }
    }
}
</script>

<style scoped>
</style>
