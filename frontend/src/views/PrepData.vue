<template>
  <div class="bg-gray-300 shadow-inner">
    <div class="w-2/3 mx-auto py-4">
      <Timer v-bind:time="180" to="prep_video" from="prep_data" class="p-4" />
      <DataEntry class="w-3/4 mx-auto" />
      <!-- <Submissions /> -->
    </div>
  </div>
</template>

<script>
import DataEntry from "@/components/DataEntry.vue";
import Timer from "@/components/Timer.vue";
// import Submissions from "@/components/Submissions.vue";
export default {
  name: "PrepVideo",
  components: {
    Timer,
    DataEntry,
    // Submissions,
  },
  mounted() {
    alert("Are you ready to begin?");
  },
};
</script>
