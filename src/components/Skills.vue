<template>
    <div class="entry">
        <ul class="works">
          <li><a><img src="../assets/azure.jpg" alt="Azure"></a></li>
          <li><a><img src="../assets/azure_functions.png" alt="Azure Functions"></a></li>
          <li><a><img src="../assets/typescript.png" alt="Typescript"></a></li>
          <li><a><img src="../assets/vue.png" alt="Vue"></a></li>
        </ul>
    </div>
</template>

<script lang="ts">
  import { defineComponent } from 'vue';

  export default defineComponent({
    name: "Skills",
  });
</script>