<template>
    <div class="mb-20 mt-20 feature">
        <div class="text-center">
            <About/>
        </div>
        <div class="flex justify-center mt-5">
            <Feat/>
        </div>
        <div class="flex justify-center">
            <Video/>
        </div>
    </div>
</template>

<script>
import Feat from "./Feat.vue";
import About from "./About.vue";
import Video from "./Video.vue";
export default {
  name: "Features",
  components: {
    Feat,
    About,
    Video,
  },
};
</script>

<style scoped>
 
</style>