<script>
export default {
  name: "add-hero-btn",
  props: {
    buttonName: String,
  },
};
</script>

<template>
  <a
    class="f6 link dim br3 ph3 pv2 mb2 dib white bg-black"
    @click="$emit('add-hero', true)"
    >{{ buttonName }}</a
  >
</template>
