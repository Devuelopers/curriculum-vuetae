<template>
  <div class="entry">
    <img class="portrait" src="../assets/logo.png" alt="Leonardo B. Tosin"/>
    <div class="self">
      <h1 class="name">Your name</h1>
      <ul>
        <li class="ad">City - State - Country</li>
        <li class="mail">my@email.com</li>
        <li class="web"><a href="#">My website</a></li>
      </ul>
    </div>
    <div class="social"></div>
  </div>
</template>

<script lang="ts">
  import { defineComponent } from 'vue';

  export default defineComponent({
    name: "Profile",
  });
</script>