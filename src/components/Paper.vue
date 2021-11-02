<template>
    <div id="paper">
        <div class="paper-top"></div>
        <PaperContent />
    </div>
</template>

<script lang="ts">
  import { defineComponent } from 'vue';
  import PaperContent from './PaperContent.vue'

  export default defineComponent({
    components: { PaperContent },
    name: "Paper",
  });
</script>