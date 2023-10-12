<template>
  <nav>
    <ul>
      <li>
        <button @click="toHome">Home</button>
      </li>
      <li>
        <button @click="toReact">React</button>
      </li>
    </ul>
  </nav>
</template>

<script setup>
const toHome = () => window.singleSpaNavigate('/home');
const toReact = () => window.singleSpaNavigate('/react');
</script>

<style>
/* Add your styles for the navigation bar here */
</style>
