<template>
  <div class="child">
    <h5>Child One</h5>
    <button @click="clickMe">Click Me Child One</button>
  </div>
</template>

<script>
export default {
  name: "ChildOne",
  methods: {
    clickMe() {
      this.$emit("childOne", "Hello World");
    },
  },
};
</script>
