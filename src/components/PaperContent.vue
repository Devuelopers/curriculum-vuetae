<template>
    <div id="paper-mid">
        <Profile />
        <div class="entry">
            <Presentation />
            <Education />
            <Experience />
            <Skills />
        </div>
    </div>
</template>

<script lang="ts">
  import { defineComponent } from 'vue';
  import Education from './Education.vue'
  import Experience from './Experience.vue'
  import Profile from './Profile.vue';
  import Presentation from './Presentation.vue'
  import Skills from './Skills.vue'

  export default defineComponent({
    components: {
        Education,
        Experience,
        Profile,
        Presentation,
        Skills
    },
    name: "PaperContent",
  });
</script>