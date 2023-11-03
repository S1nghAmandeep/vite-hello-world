<script>
// import HelloWorld from './components/HelloWorld.vue'
import AppHero from './AppHero.vue'

export default {
  data() {
    return {
      message: 'La mia prima app con Vite!'
    };
  },
  components: { AppHero }
}
</script>

<template>
  <div>
    {{ message }}
    <AppHero />

  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
