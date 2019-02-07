<template>
  <div id="app">
    <navbar />
    <home />
    <foot />
  </div>
</template>

<script>
import navbar from './components/navbar.vue'
import home from './components/home.vue'
import foot from './components/foot.vue'

export default {
  name: 'app',
  components: {
    navbar,
    home,
    foot
  }
}
</script>
