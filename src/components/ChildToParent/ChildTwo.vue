<template>
  <div>
  <h5>ChildTwo</h5>
  <p>{{ yolla }}</p>
    <p>{{ kelime }}</p>
    <p>{{ gonder }}</p>
  <button @click="clickMe">Click Me Change Message</button>
  </div>
</template>

<script>
export default {
  name: "ChildTwo",
  props: ["yolla", "kelime", "gonder"],
  methods: {
    clickMe() {
      this.yolla = [1, 3, 5];
      this.kelime = "naber";
      this.gonder = {"gulben": "selam yalnizlik ben geldim"}
    },
  },
};
</script>
