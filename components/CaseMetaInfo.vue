<template>
  <div
    class="meta br-10 px-40 py-40"
  >
    <div>
      <p class="ff-small-caps fs-14">👩🏾‍💻 ROLE</p>
      <p class="fs-18">{{ role }} <span class="fs-14" style="opacity: 0.6">{{ roleNotes }}</span></p>
    </div>
    <div class="pt-20">
      <p class="ff-small-caps fs-14">🛠 TOOLS</p>
      <p class="fs-18">{{ tools }}</p>
    </div>
    <div v-if="process" class="py-20">
      <p class="ff-small-caps fs-14">🚗 PROCESS</p>
      <p class="fs-18">{{ process }}</p>
    </div>
    <div>
      <p class="ff-small-caps fs-14">⏳ DURATION</p>
      <p class="fs-18">{{ duration }}</p>
    </div>
  </div>
</template>


<script>
export default {
  props: {
    role: String,
    roleNotes: String,
    tools: String,
    duration: String,
    process: String,
  },
};
</script>

<style lang="scss" scoped>
.meta {
  // grid-column: 1/9;
  // @include desktop {
  //   grid-column: 2/5;
  // }
  // @include large-desktop {
  //   grid-column: 6/9;
  // }
}
</style>