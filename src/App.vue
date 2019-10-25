<template>
  <div id="app">

    <!--<HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <cabecera></cabecera>
    <AsideComponent></AsideComponent>
    <contenido/>
    <FooterComponent/>
  </div>
</template>

<script>

import cabecera from './components/cabecera.vue'
import AsideComponent from './components/asides.vue'
import contenido from './components/contenido.vue'
import FooterComponent from './components/FooterComponent.vue'

export default {
  name: 'app',
  components: {
    cabecera,
    AsideComponent,
    contenido,
    FooterComponent
  }
}
</script>

<style>

</style>
