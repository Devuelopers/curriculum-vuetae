<template>
    <div class="entry">
      <h2>EXPERIENCE</h2>
      <div class="content">
        <h3> From - currently</h3>
        <p>Role<br />
        <em>Company</em>
        <b>Stack:</b> Vue, Typescript and Azure
        </p>
        <ul class="info">
          <li>An activity I did</li>
          <li>Some another activity</li>
        </ul>
      </div>
      <div class="content">
        <h3> From - To</h3>
        <p>Role<br />
        <em>Company</em>
        <b>Stack:</b> Vue, Typescript and Azure
        </p>
        <ul class="info">
          <li>An activity I did</li>
          <li>Some another activity</li>
        </ul>
      </div>
    </div>
</template>

<script lang="ts">
  import { defineComponent } from 'vue';

  export default defineComponent({
    name: "Experience",
  });
</script>