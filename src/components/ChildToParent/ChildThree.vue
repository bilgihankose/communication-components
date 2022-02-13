<template>
  <div class="child">
    <p>This is Child 3</p>
    <p>{{ childVerisi }}</p>
    <input type="text" v-model="childVerisi" />
    <button @click="yolla">Parenta Yolla</button>
  </div>
</template>

<script>
export default {
  name: "ChildThree",
  data() {
    return {
      childVerisi: "",
    };
  },
  computed: {
    yolla() {
      return {
        this: this.$emit("gonder", this.childVerisi),
      };
    },
  },
};
</script>
