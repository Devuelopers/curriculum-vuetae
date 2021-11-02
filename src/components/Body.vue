<template>
    <div class="wrapper-top"></div>
    <div class="wrapper-mid">
    <Paper />
    </div>
</template>

<script lang="ts">
  import { defineComponent } from 'vue';
  import Paper from './Paper.vue';

  export default defineComponent({
    components: { Paper },
    name: "Body",
  });
</script>