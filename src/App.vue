<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <div class="wrapper">
      <img alt="Vue logo" class="logo" src="./assets/IMG_0997.jpg" />
      <HelloWorld msg="My Curriculum Vitae" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
  text-align: center; /* Center-align content */
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh; /* Full viewport height */
}

.logo {
  display: block;
  margin: 0 auto 2rem; /* Center the logo and add space below */
  width: 500px; /* Adjust the size of the logo */
  height: 500px; /* Adjust the size of the logo */
}

.wrapper {
  display: flex;
  flex-direction: column; /* Stack items vertically */
  align-items: center; /* Center items horizontally */
  gap: 2rem; /* Add more space between elements */
}

@media (min-width: 1024px) {
  header {
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 0 2rem; /* Center the logo and add space below */
  }

  header .wrapper {
    display: flex;
    flex-direction: column; /* Ensure vertical stacking on larger screens */
    place-items: center; /* Center items horizontally */
  }
}
</style>
 