<template>
    <footer>
        <p>Created By Leonardo Tosin - Copyright {{ currentYear }}</p>
    </footer>
</template>

<script lang="ts">
  import { defineComponent } from 'vue';

  export default defineComponent({
    name: "Footer",
    computed: {
      currentYear()  {
        return new Date().getFullYear()
      }
    }
  });
</script>