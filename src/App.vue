<script>
export default {
  // questo é il vs options object
  data(){
    return{
      title: 'Hello Vite',
    }

  },
  
}
</script>

<template>
  // your markup here
  <h1>
    Hello Vite! {{ title }}
  </h1>
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
