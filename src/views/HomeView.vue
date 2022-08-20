<template>
  <div class="home">
      <NavBar/>
      <PageInicial/>
      <LeiaMais/>
      <Populares/>
  </div>
</template>

<script>

import NavBar from '@/components/NavBar.vue';
import PageInicial from '@/components/PageInicial.vue';
import LeiaMais from '@/components/LeiaMais.vue'
import Populares from '@/components/Populares.vue'

export default {
  name: 'HomeView',
  components: {
      NavBar,
      PageInicial,
      LeiaMais,
      Populares
  }
}
</script>
