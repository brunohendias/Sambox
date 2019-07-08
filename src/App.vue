<template>
  <div id="app">
    <MenuNav />
    <Cabeca />
    <Info />
    <Services />
    <Contact />
  </div>
</template>

<script>
import MenuNav from '@/components/menuNav.vue'
import Cabeca from '@/components/cabeca.vue'
import Info from '@/components/info.vue'
import Services from '@/components/services.vue'
import Contact from '@/components/contact.vue'

export default {
  name: 'app',
  components: {
    MenuNav,
    Cabeca,
    Info,
    Services,
    Contact
  }
}
</script>