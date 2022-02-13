<template>
  <div class="child">
    <h5>Child Two</h5>
    <input type="text" v-model="message" @keyup="clickMe" />
  </div>
</template>

<script>
export default {
  name: "ChildTwo",
  data() {
    return {
      message: "",
    };
  },
  methods: {
    clickMe() {
      this.$emit("childTwo", this.message);
    },
  },
};
</script>
