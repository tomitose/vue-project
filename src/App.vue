<script setup lang="ts">
import CounterOption from './components/CounterOption.vue';
import PostButton from './components/PostButton.vue';
import PostContainer from './components/PostContainer.vue';

</script>

<template>
  <header>
    <img  alt="Vue logo" class="logo " src="./assets/logo.svg" width="125" height="125" />
    <h1 class="text-red-500">Hola!</h1>
  </header>

  <PostContainer/>
  <CounterOption/>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    margin: 10px;
    display: flex;
    place-items: center;
    flex-wrap: wrap;
    justify-content: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
